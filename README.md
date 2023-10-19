![Jdbi Logo](/images/logo.svg)

The Jdbi library provides convenient, idiomatic access to relational databases in Java and other JVM technologies such as Kotlin, Clojure or Scala.

Jdbi is built on top of JDBC. If your database has a JDBC driver, you can use Jdbi with it.

* [Developer Guide](https://jdbi.github.io/)
* [Javadoc](https://jdbi.org/apidocs/)
* [User forums](https://github.com/jdbi/jdbi/discussions)
* [Mailing List](http://groups.google.com/group/jdbi)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/jdbi)

**Jdbi provides convenient, idiomatic, access to relational data in Java.** Jdbi 3 is the third major release, which introduces enhanced support for modern Java, countless refinements to the design and implementation, and enhanced support for modular development through plugins and extensions.

**Jdbi is built on top of JDBC.** If your data source has a JDBC driver, you can use it with Jdbi. It improves JDBC's low-level interface, providing a more natural API that is easy to bind to your domain data types.

**Jdbi is not an ORM.** It is a convenience library to make Java database operations simpler and more pleasant to program than raw JDBC. While there is some ORM-like functionality, Jdbi goes to great length to ensure that there is no hidden magic that makes it hard to understand what is going on.

**Jdbi does not hide SQL away.** One of the design principles of Jdbi is that SQL is the native language of the database, and it is unnecessary to wrap it into code, deconstruct it, or hide it away. Being able to express a query in raw SQL makes it possible for programmers and data engineers to speak the same language and not fight translation layers.

**Jdbi does not aim to provide a complete database management framework.** It provides the building blocks that allow constructing the mapping between data and objects as appropriate for your application and the necessary primitives to execute SQL code against your database.
