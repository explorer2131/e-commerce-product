# E-Commerce Product Management System

This project uses Node.js, Express and MySQL.

## Requirements
- Node.js
- MySQL Server

## Setup
1. Open the project folder in VS Code.
2. Open MySQL and run `database/schema.sql` in MySQL Workbench or another MySQL client.
3. Copy `.env.example` and rename the copy to `.env`.
4. Put your local MySQL password in `.env`.
5. Open the VS Code terminal.
6. Run `npm install`.
7. Run `npm start`.
8. Open `http://localhost:5000` in a browser.

## Default database settings
- Host: localhost
- Port: 3306
- User: root
- Database: ecommerce_product

Change the `.env` values if your MySQL installation uses different settings.

## Important
Do not upload `.env` to GitHub. Keep `.env.example` in the repository as a configuration template.
