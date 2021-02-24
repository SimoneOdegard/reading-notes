# Read 13

## The Past, Present, and Future of Local Storage for Web Applications
[Link to article](http://diveinto.html5doctor.com/storage.html)

Downsides of using cookies:
- Included with every HTTP request so it slows down your web application
- Sends data unencrypted over the internet
- Cookies are limited to 4 KB of data and that's enough to slow your application.

userData allows web pages to store up to 64 KB of data per domain. Local Shared Objects allows Flash objects to store up to 100 KB of data per domain. There is a pattern where all of them are specific to a single browser or reliant on a third-party plugin. However, they expose different interfaces, different storage limitations, and different user experiences. HTML5 set out to solve these issues.

HTML5 Storage is a way for web pages to store name key/value pairs locally. The data is never transmitted to the remote web server.

There are some limitations of HTML5 Storage.
- 5 megabytes: how much storage space each origin gets by default.
- QUOTA_EXCEEDED_ERR: the exception that will get thrown if you exceed your storage quota of 5 megabytes.
- no: the answer for "Can I ask the user for more storage space?"

[<== Back](https://simoneodegard.github.io/reading-notes/)