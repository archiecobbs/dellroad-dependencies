# dellroad-dependencies

This project provides a parent Maven project that attempts to define a self-consistent set of dependency versions for common dependencies.

It inherits from [Spring Boot Dependencies](https://spring.io/projects/spring-boot) and then adds some more stuff. As such, the version number of this project is always equal to the version number of the `spring-boot-dependencies` parent project plus an additional number (to allow for bug fixes).
