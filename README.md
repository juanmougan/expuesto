# Expuesto

Yet another blog-like example, using:

- Spring Boot
- Exposed
- Kotlin
- FlywayDB
- Etc

## Roadmap

- Create a basic example with Docker + PostgreSQL
- Add the first entity: `Posts`, add Flyway's migrations. Add some superflous column, so it can be dropped eventually
- Add a service and its tests (hello, TestContainers!)
- Add `TextComments`, and map the entities accordingly
- Add `AudioComments`, and map the entities accordingly (just a fake pointer somewhere, but these two sound polymorphic - maybe use JSON support here)
- Add a query that retrieves a `Post`and both type of comments
- Add the web layer and tests for controllers
- Make sure the migrations support dropping the extra column for `Posts`

## Resources

- [Baeldung](https://www.baeldung.com/kotlin/exposed-persistence)
- [Spring example](https://github.com/JetBrains/Exposed/tree/main/samples/exposed-spring)
- [Set up Exposed with Flyway](https://bettercoding.dev/kotlin/tutorial-exposed-generation-flyway/)
