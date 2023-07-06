# E-commerce Back End

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```


# E-commerce Back End

## Usage

To use this e-commerce back end, follow these steps:

1. [E-Commerce Back End Repository](https://github.com/jamalm06/e-com-backend)
   - Navigate to the E-Commerce Back End repository on your personal GitHub account.

2. Clone the repository:
   - Copy the SSH key of the repository.
   - Open your preferred coding platform (e.g., VS Code).
   - Right-click on a desired location to clone the repository.
   - Select "Open in Integrated Terminal."
   - In the terminal, enter the command:
     ```
     git clone [SSH key]
     ```

3. Install dependencies:
   - In the terminal, navigate to the "E-COMMERCE-BACK-END" folder.
   - Enter the command:
     ```
     npm install
     ```

4. Set up the database:
   - In the terminal, enter the command:
     ```
     mysql -u root -p
     ```
   - Enter the password located in the `.env` file when prompted.
   - Enter the command to load the database:
     ```
     source db/schema.sql
     ```
   - Type `exit` to exit MySQL.

5. Populate the database:
   - In the terminal, enter the command:
     ```
     npm run seed
     ```

6. Start the server:
   - In the terminal, enter the command:
     ```
     npm start
     ```

7. Test the routes:
   - Open an API testing tool like Insomnia.
   - Test the available routes (GET, GET by ID, POST, PUT, DELETE) for the CATEGORY, PRODUCT, and TAG models.

Feel free to reach out if you have any questions or need further assistance. Happy coding!



Video link for demonstration is [here](https://drive.google.com/file/d/1hORVL0nEvu20ZfOo3lXkWrGYxN9PKfG3/view)
