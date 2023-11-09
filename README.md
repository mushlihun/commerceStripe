# Ecommerce-Vita:

Laravel E-commerce project. E-commerce platform with REST Api, Multiple Auth (admin , editor , user) and admin panel integration.

## Features:
- Authentication and Authorization (Breeze Starter kit)
- Multiple Authentication (Admin, Editors, Users)
- Search (Name, Tag, SKU)
- Reports
- Chart report
- Add dynamic product Attributes
- Coupon
- Shipping
- payment gateway
- Site settings
- Mobile First Design


![Dashboard](https://i.ibb.co/zb5z8jw/spa1.png)

## Run Locally:

Clone the project:

```bash
  git clone https://github.com/mushlihun/commerceStripe.git
```

Go to the project frontend directory:

```bash
  cd commerceStripe/frontend
```

Install frontend dependencies:
# vue

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

Run frontend:

```bash
  npm run dev
```

Go to the project backend directory:

First open new terminal.

```bash
  cd commerceStripe/backend
```

Install dependencies:

```bash
  composer install
  npm install
```
Create .env file and copy .env.example to .env, create database name and add into .env database name.

Key Generate
```bash
php artisan key:generate
```
Storage Link
```bash
php artisan storage:link
```

Migrate database:

```bash
php artisan migrate --seed
```

Run project:

```bash
php artisan serve
```
Open: http://127.0.0.1:8000

**If you work with order, add stripe key and mail config in .env**

## Screenshots

![Admin Dashboard](https://i.ibb.co/zb5z8jw/spa1.png)
![Orders Table](https://i.ibb.co/LhMVYzY/spa2.png)
![Customers Orders Reports](https://i.ibb.co/9WNRVmw/spa3.png)
![Orders Chart](https://i.ibb.co/phgCVbw/spa7.png)
![Settings](https://i.ibb.co/vsGPXpN/spa5.png)


## Tech Stack

**Client:** Vue.js, Pinia, Axios, Bootstrap, sweetalert2

**Server:** PHP8.2, Laravel10.x, Liveware, Bootstrap


## Authors

- [@mushlihun](https://www.github.com/mushlihun)
