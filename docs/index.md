# OpinAPI
OpinAPI is opinionated API framework for building REST services with FastAPI, SQLAlchemy and more predefined popular libraries.

The key features are:

* **Opinionated**: Create standardized applications with predefined software stack, project structure and architecture concepts.
* **FastAPI**: Based on FastAPI, a modern, fast (high-performance), web framework for building APIs with Python.
* **SQLAlchemy**: Based on SQLAlchemy, a SQL toolkit and Object-Relational Mapping (ORM) library for Python.
* **Flexible**: Allows bypassing the opinionated concepts and use directly FastAPI and SQLAlchemy as you like.
* **Open Standards**: Solve common problems with open standards like RFCs, JSON:API, OpenAPI, OAuth 2.0, etc.

## Opinionated Concept

The idea of having an opinionated framework is to provide a standardized software stack, project structure and architecture
concepts. This allows developers to focus on the business logic and not on the technical decisions. Some opinionated
decisions may be considered as too strict, but keep in mind that the **common sense must prevail** and the
**flexibility is always an option**.

## Decisions

Here the first opinionated decisions:

* **English**: The code, comments, documentation, etc. **must** be in Standard American English.
* **FastAPI**: REST API are built with FastAPI, that provide directly OpenAPI and JSON Schema.
* **SQLAlchemy**: SQL Database access is done with SQLAlchemy that provide ORM and SQL Toolkit.
* **Pydantic**: Pydantic **must** always be used for data validation and settings management. Don't use `dataclasses`.
