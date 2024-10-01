# Example of a good and clean application architecture in Golang with framework Gin.

in this example, I demonstrate how to structure a scalabel, maintainable and clean web application using Golang and the Gin framework. I`ll use key Go concepts like clean separation of concerns, dependency injection and efficient error handling.

## List of used libraries/utilits/frameworks:
* ```"github.com/gin-gonic/gin"``` - One of the best Golang frameworks for building HTTP applications. <a href="https://gin-gonic.com/">Gin</a>
* ```"github.com/gin-contrib/cors"``` - To handle Cross-Origin Resource Sharing (CORS), allowing secure cross-origin-requests. <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS">Mozilla Documentation</a>
* ```"github.com/google/uuid"``` - For generating and handle UUIDs. <a href="https://pkg.go.dev/github.com/google/uuid">Golang documentation</a>
* ```"github.com/jmoiron/sqlx"``` - For enhanced database interactions and query handling. **Note**: this library may be deprecated, but it is chosen to simplify the code in the tutorial. <a href="http://jmoiron.github.io/sqlx/">SQLX</a>.

## The project follows a hybrid architecture combining **Domain-Driven Design DDD** and **Clean Architecture** principles.
1. **main.go**: Application entry point, where
