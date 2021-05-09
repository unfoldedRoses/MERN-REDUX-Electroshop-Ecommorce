# ElectroShop eCommerce 

> eCommerce platform built with the MERN stack & Redux.

![Screenshot from 2021-05-07 11-38-35](https://user-images.githubusercontent.com/60324608/117572615-54b9c600-b0f1-11eb-85f9-875508609f3f.png)
![Screenshot from 2021-05-07 11-38-35](https://user-images.githubusercontent.com/60324608/117572631-60a58800-b0f1-11eb-9f2e-ddc3be774852.png)![Screenshot from 2021-05-07 11-39-56](https://user-images.githubusercontent.com/60324608/117572651-731fc180-b0f1-11eb-8e6d-10f568aeeac0.png)
![Screenshot from 2021-05-07 11-42-29](https://user-images.githubusercontent.com/60324608/117572658-774bdf00-b0f1-11eb-891c-6c221e92e566.png)
![Screenshot from 2021-05-07 11-43-15](https://user-images.githubusercontent.com/60324608/117572660-79ae3900-b0f1-11eb-980d-3855535f7d47.png)
![Screenshot from 2021-05-07 11-45-44](https://user-images.githubusercontent.com/60324608/117572663-7ca92980-b0f1-11eb-8373-ad65f2ffc3d7.png)

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)

- Database seeder (products & users)

## Note on Issues

Please do not post issues here that are related to your own code when taking the course. Add those in the Udemy Q/A. If you clone THIS repo and there are issues, then you can submit

## Usage

### ES Modules in Node

We us ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error


You can also install and setup Babel if you would like

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'

```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```

