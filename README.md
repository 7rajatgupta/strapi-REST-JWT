# Description

A REST API with authentication using JWT providing different roles and permissions for different clients and users. Also features a Employees specific role which can be used to modify data and POST request directly to the server.

Has a nice Admin dashboard to manage your application structure.

## Features:

- REST API with JWT.
- Local and Auth Users.
- Relations
- Admin Dashboard for quick management.
- Role specific permissions.
- Support for Lifecycle methods with data.
- Methods for `fetchAll(), fetch(context) fetchOne(id), Add(), Update(), Delete()`
- Support for Overriding Default methods and Services. Check `api/category/controllers/category.js`
- Pre-built controllers, api and config.

## Usage:

This repository can be used as a general template providing you the basic arch and setup which you can use to build on top of. Provides 2 default users -> `Employee1` and `Client1` for your employee/partners and clients coupled with suitable permissions.

Illustrated how to override methods of controllers and services. Check the services file for proper docs.
Feel free to fork this repo and add new REST features.
