# Docker App

## Cloning the Project

To clone this project, run the following command:

```bash
git clone https://github.com/iuzairsaeed/docker-laravel.git
cd docker-laravel/
```

## Running the Project

After you have updated your `docker-compose.yml` and `Dockerfile`, follow these steps to build and run your Laravel project with PHP 8.3:

### Build the Containers

```bash
docker-compose build
```

### Start the Containers

```bash
docker-compose up -d
```

### Access the Application

Open your web browser and navigate to [http://localhost:80](http://localhost:80) to see your Laravel application running.

## Database Configuration in Laravel

Make sure to update the `.env` file in your Laravel project with the correct database configuration:

```env
DB_CONNECTION=mysql
DB_HOST=your_database_host
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```
