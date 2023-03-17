# Signup and Login Form

JavaFX user registration app connected to database! 

Built with:
- Java
- JavaFX
- Maven
- MySQL

![Signup and Login Form Gif](https://user-images.githubusercontent.com/115106367/225999257-8031ca56-da50-46ed-a880-79e5f025dd1a.gif)

Input data is synchronized with database!

![MySQL Synchronization](https://user-images.githubusercontent.com/115106367/225999975-bdc5fa88-f841-4653-9d4e-3754da9505c8.jpg)

## Installation

Programs required:
- IDE IntelliJ IDEA
- JavaFX 19.0.2.1
- MySQL Workbench 8.0.32

Before running program:

- Setup JavaFX for your IDE:

https://openjfx.io/openjfx-docs/#introduction

- Create JavaFX Maven Project:

![Maven Configuration 1](https://user-images.githubusercontent.com/115106367/226014227-232df634-ad6b-472a-a7a8-c203ca2e84b4.jpg)

![Maven Configuration 2](https://user-images.githubusercontent.com/115106367/226014272-88481621-2111-4448-ba90-a88b22bf82df.jpg)

- Replace "src" folder and "pom.xml" file with downloaded files:

![App Configuration 1](https://user-images.githubusercontent.com/115106367/226015436-b6c040f8-d3a6-46c3-a739-96da62eaeaf3.jpg)

![App Configuration 2](https://user-images.githubusercontent.com/115106367/226015539-d1904476-74a5-4cc2-bde4-3f941a108caf.jpg)

- After replacing files you should see downloaded "External Libraries":

![App Configuration 3](https://user-images.githubusercontent.com/115106367/226015577-47db7067-3b11-434b-862c-4df402813c87.jpg)

- Add new connection on MySQL Workbench:

![MySQL Server Setup](https://user-images.githubusercontent.com/115106367/224393983-2f199efc-5137-46f7-ab48-01795bf752cd.jpg)
- Setup MySQL Schema:

![MySQL Creation](https://user-images.githubusercontent.com/115106367/226012200-7f3cf2ff-e403-4313-bd97-95fdc057009e.jpg)

- Search for "jdbc:mysql:" and insert YOUR database information in "DatabaseUtils.java" file:

![JDBC Connection](https://user-images.githubusercontent.com/115106367/226013513-8ecd667f-3f32-4d24-8f5a-63ca2957f940.jpg)

### How to run program?

If everyting is setup corectly you should be able to run the program by typing: "mvn clean javafx:run" in terminal:

![App Configuration 4](https://user-images.githubusercontent.com/115106367/226018094-edfb04c9-5da5-49b4-b53f-a02417e40d5b.jpg)

![App Configuration 5](https://user-images.githubusercontent.com/115106367/226018191-f605e9e3-3b55-4090-907b-3fc737923517.jpg)




