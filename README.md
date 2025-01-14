# Manar El Gorchi's Ecommerce Website (Symfony Exam Project)

This project is an ecommerce website built using Symfony. It showcases collections of both men's and women's fashion, with an easy-to-use admin panel to manage the website's content.

## Project Features

- **Homepage**: Displays the latest collections of men's and women's fashion.
- **Product Pages**: Each product has a dedicated page with detailed information, including images, sizes, and descriptions.
- **Back Office**: Powered by EasyAdmin, allowing easy management of products, categories, and user interactions.
- **Responsive Design**: The website is built using Bootstrap to ensure it is fully responsive on all screen sizes.
- **Twig Templates**: Uses Twig for flexible templating and clean separation of logic and presentation.

## Technologies Used

- **Symfony 5.10.6**: The PHP framework used to build the website.
- **PHP 8.1**: The programming language for server-side logic.
- **MySQL**: Database management system for storing product information and user data.
- **Bootstrap**: Frontend framework used to build the responsive design.
- **EasyAdmin**: Admin panel package for Symfony to manage the ecommerce content.
- **Twig**: Templating engine for clean HTML rendering.

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/ecommerce-project.git
    cd ecommerce-project
    ```

2. **Install dependencies using Composer**:
    ```bash
    composer install
    ```

3. **Set up your environment**:
    - Create a `.env.local` file and set the appropriate database and environment settings.

4. **Create the database**:
    ```bash
    php bin/console doctrine:database:create
    ```

5. **Run migrations to create the necessary tables**:
    ```bash
    php bin/console doctrine:migrations:migrate
    ```

6. **Start the Symfony server**:
    ```bash
    symfony server:start
    ```

7. **Visit the site** in your browser at [http://localhost:8000](http://localhost:8000).


## Project Structure

- **`/src`**: Contains the application's business logic, controllers, entities, and other custom code.
- **`/templates`**: Contains all the Twig templates for rendering the frontend views.
- **`/public`**: Contains public assets like images, CSS, and JavaScript.
- **`/config`**: Contains configuration files for Symfony services and routing.