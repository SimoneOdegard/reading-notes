# Read 12

## nosql vs sql
[link](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

SQL = structured query language
NoQL = unstructured query language

SQL vs NoSQL
- SQL databases are are Relational Databases while NoSQL are non-relational or distributed database.
- SQL are table based vs NoSQL are document based
- SQL have predefined schema vs NoSQL have dynamic schema for unstructured data
- SQL is vertically scalable vs NoSQL horizontally scalable
- SQL good fit for complex query intensive enviornment vs NoSQL isn't as powerful and doesn't have standard interfaces to perform complex queries
- SQL not good for hierarchical data storage vs NoSQL fits better with hierarchical data storage
- SQL

SQL Database Examples
1. MySQL Community Edition: popular open-source database.
1. MS-SQL Server Express Edition: powerful and user friendly. Has support from Microsoft
1. Oracle Express Edition: free for development and deployment

NoSQL Database Examples
1. MongoDB: most popular document based NoSQL database. Stores data in JSON docs
1. CouchDB: stores data in form of JSON docs.
1. Redis: mainly used because of its speed.

## nosql modeling techniques
[link](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/)

General notes on NoSQL data modeling:
- starts from the application-specific queries
- NoSQL you need a deeper understanding of data structures and algorithms.
- Relational databases are not convenient for hierarchical/graph-like data modeling.

Conceptual Techniques:
1. Denormalization: copying of the same data into multiple documents or tables in order to simply/optimize query processing. This also means you fit the data into a data model.
1. Aggregates: NoSQL provides soft schema capabilities. Soft schema allows one to form nested entities which are classes of entities with complex internal structures. It varies the structure of the particular entities.
1. Application Side Joins: Joins are handled at design time as opposed to relational models where joins are handled at query execution time. You can avoid joins using Denormalization and Aggregates.

Modeling Techniques
1. Atomic Aggregates: Lets you store a single business entity as one document, row, or key-value pair. It will update it atomically.
1. Enumerable Keys: Unordered Key-Value data models can be partitioned across multiple servers by using the key. Sorting makes things more complex.
1. Dimensionality Reduction: Allows you to map multidimensional data to a Key-Value model. You can also do this with other non-multidimensional models.
1. Index Table: Allows youto take advantage of indexes in stores that do not support indexes internally.
1. Composite Key Index: In conjunction with sorting lets you build a multidimensional index that is fundamentally similar to Dimensionality Reduction.
1. Aggregation with Composite Keys: Used for different types of grouping.
1. Inverted Search - Direct Aggregation: A data processing pattern instead of data modeling. Use index to find data that meets a criteria. The aggregate data uses the original representation/full scans.

Hierarchy Modeling Techniques
1. Tree Aggregation: Can be modeled as a single record or document.
1. Adjacency Lists: More straightforward way to graph modeling. Each node is modeled as independent records. They contain arrays of ancestors/descendants. You can search for nodes by indentifiers of parents/children as well as traverse a graph one hop per query.
1. Materialized Paths: Helps avoid recursive traversals. THis is a kind of Denormalization. You can attribute each node by identifiers of all its parents or children. It makes it easier to see all descendants/ancestors of the node without traversal.
1. Nested Sets: Standard technique for modeling tree-like structures. Used in relational databases but applicable to Key-Value Stores and Document Databases. You would store the leafs of the tree in an array and map each non-leaf node so that leafs can start using them.
1. Nested Documents Flattening: Numbered Field Names: Search engines work with flat documents. 
1. Nested Documents Flattening: Proximity Queries: You would use proximity queries to limit the acceptable distance between worlds in the document.
1. Batch Graph Processing: Using this technique makes Key-Value stores, Document databases, and BigTable-style databases become suitable for porcessing large graphs.

[<== Back](https://simoneodegard.github.io/reading-notes/)