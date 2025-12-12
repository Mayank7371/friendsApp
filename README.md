# FriendsApp

A simple and clean ***CRUD** web application built using **Ruby on Rails**, **PostgreSQL**, and **TailwindCSS**.  
This app allows users to manage a list of friends with fields like first name, last name, email, phone, and Twitter handle.

---

## Features

- Add new friends  
- View list of all friends  
- Edit friend details  
- Delete friends  
- Responsive layouts with header + footer  
- PostgreSQL-backed database  
- Rails scaffold-generated structure

---

## Tech Stack

| Component     | Technology          |
|---------------|---------------------|
| Backend       | Ruby on Rails 8     |
| Database      | PostgreSQL          |
| Frontend      | TailwindCSS         |
| Rendering     | Turbo / Rails Views |
| Server        | Puma                |

---

## 📦 Installation & Setup

### 1. Clone the Repository

```sh
git clone https://github.com/yourusername/crud-app.git
cd crud-app
bundle install
rails db:create
rails db:migrate
rails tailwindcss:install
rails s
http://localhost:3000
```

