# Read 13

## Sending Form Data
[link](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data)

"When the form data has been validated on the client-side, it is okay to submit the form." (Article).

What happens with the form is submitted:
Client/server architecture. a client sends a request to the server. The server responds to the request using the same protocol.

Client side defining how to send the data: Form element defines how the data is sent. Attributes are designed to configure the request to be sent when a user hits a submit button. The most important attributes are action and method. **Action** defines where the data gets sent. **Method** defines how the data is sent.

- GET method is used by the browser to ask the server to send back a given resource.
- POST method is the method the browser uses to talk to the server. When asking for a request, it looks at the data provided in the body of the HTTP.

To view HTTP requests, you need to use tools like Firefox Network Monitor or Chrome Developer Tools because the requests are never displayed.

Server side: retrieving the data
- Raw PHP: offers global objects to access the data. If you used the POST method, the following examples just take the data and displays it to the user.
- Python
- Other languages

Sending files
Enctype attribute: "This attribute lets you specify the value of the Content-Type HTTP header included in the request generated when the form is submitted. The header is important because it tells the server what kind of data is being sent." (Article) 

Security issues
HTML forms are the most common server attack vectors. The problems comes from how the server handles data. **Be paranoid. Never trust your users**.

[<== Back](https://simoneodegard.github.io/reading-notes/)