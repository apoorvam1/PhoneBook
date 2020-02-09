# PhoneBook
Gradle based REST API for creating phone book using SpringBoot and Protobuf

This project creates REST API using Spring Boot to perform below operations:

Create a new contact
- Update an existing contact
- Delete a contact
- View a contact
- View list of contact names
- Uses protobuf to generate POJOs for the phonebook.

*Build management - Gradle*

Run `gradle clean build` compile to compile the code base.

The compiled classes will be generated at the `build` folder. You can also see that the compiled classes for proto files will be generated at `build/generated/source/proto/main/java/phonebook`