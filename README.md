# CS208 Full Stack Lab - TODO List

- Name: Connor Allen
- GitHub: [https://github.com/callenBSU](https://github.com/callenBSU)
- Term: Summer 2026

## Project Description

Full-stack web dev assignment for CS208 Summer. This is a basic to-do list that allows you to add, edit, delete, and check off tasks. Note: to check off a task, click Edit and check off "mark as completed"

## Install the Database

Run the following script in your terminal. Make sure you are in Github codespaces instead of the windows vscode app.

```bash
./setup_scripts/install_db.sh
```

## Create the Database Tables

Generate initial tables with this command:

```bash
sudo mysql -u root -p < ./setup_scripts/create_demo_table.sql
```

## Install Dependencies

Install npm dependences:

```bash
npm install
```

## Run the Application

Start app:

```bash
npm start
```

## Access the Application

Through codespaces, click on "Open in browser" once the windows pops up in the bottom right. 