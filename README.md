# Example of a good and clean application architecture in Golang with framework Gin.

in this example, I demonstrate how to structure a scalabel, maintainable and clean web application using Golang and the Gin framework. I`ll use key Go concepts like clean separation of concerns, dependency injection and efficient error handling.

## List of used libraries/utilits/frameworks:
* ```"github.com/gin-gonic/gin"``` - One of the best Golang frameworks for building HTTP applications. <a href="https://gin-gonic.com/">Gin</a>
* ```"github.com/gin-contrib/cors"``` - To handle Cross-Origin Resource Sharing (CORS), allowing secure cross-origin-requests. <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS">Mozilla Documentation</a>

## The project follows a hybrid architecture combining **Domain-Driven Design DDD** and **Clean Architecture** principles. This architecture promotes a clear separation of concerns, ensuring that business logic remains decoupled from infrastructure concerns and is easy to test, extend, and maintain. The key focus is to keep the domain at the core of the system while organizing the application into well-defined layers.
