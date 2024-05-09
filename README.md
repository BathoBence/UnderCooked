
# UnderCooked

The application provides recipes based on what you have at home. Saving you time and you'll probably end up with less expired ingredient.

## Tech Stack

**Client:** React+Vite

**Server:** Spring-Boot

**Database:** SQL

## Backend Installation

**Prerequisites**

***- Before you begin, ensure you have met the following requirements:***

- Java Development Kit (JDK) installed (version 17.0.8)

- Maven build tool installed (version 3.9.2)

- SQL database (e.g., MySQL, PostgreSQL) installed and running

- IDE (e.g., IntelliJ IDEA, Eclipse) installed for development (optional but recommended)

**Steps**

***- Clone the Repository***
```
git clone git@github.com:BathoBence/UnderCooked.git
```
***- Navigate to the Backend Directory***
```
cd /backend
```
***- Set Up the Database***

Create a new database instance in your SQL database.

Configure the database connection details using environment variables in application.properties file located in src/main/resources/ directory.

Use the seed_db file to populate the database.

***- Build the Application***
```
mvn clean install
```
***- Run the Application***
```
java -jar target/backend-<version>.jar
```
Replace <version> with the version of your application.

## Frontend Installation

**Prerequisites**

***- Before you begin, ensure you have met the following requirements:***

- Java Development Kit (JDK) installed (version 17.0.8)

- Maven build tool installed (version 3.9.2)

- SQL database (e.g., MySQL, PostgreSQL) installed and running

- IDE (e.g., IntelliJ IDEA, Eclipse) installed for development (optional but recommended)

**1.0 Prerequisites**

Before you begin, ensure you have the following prerequisites installed on your machine:

Node.js: Download and install Node.js (includes npm) https://nodejs.org/en

**1.1 Clone Repository**
```bash
  git clone "Repository"
```
**1.2 Navigate to the project directory**
```bash
  cd "project-directory"
```
**1.2 Install dependecies**
```bash
  cd frontend
  npm install
```


**1.4 Run the application**

Start the client:
```bash
cd fronted
npm start
```
This will start the client React app at http://localhost:3000

**My former team members are:**

https://github.com/DoraDru

https://github.com/Marcel-zb96

