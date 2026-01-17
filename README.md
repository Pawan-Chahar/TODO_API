
# TODO_API

A simple, modern **RESTful TODO API** built with **Python** and **FastAPI** (or Flask) + **SQLite** database.  
Perfect for learning API development, CRUD operations, and lightweight backend projects.



## ✨ Features

- **CRUD** operations for Todo items (Create, Read, Update, Delete)
- RESTful endpoints (`/todos`, `/todos/{id}`, etc.)
- Automatic interactive API documentation (Swagger UI & ReDoc)
- Clean project structure
- Dependency management with **uv** (or poetry/pip)

## 📂 Project Structure


```markdown




```bash
TODO_API/
├── api/                # API routes, endpoints, schemas
│   └── ...
├── app/                # Core application logic, models, database
│   └── ...
├── main.py             # Entry point - FastAPI app
├── pyproject.toml      # Project metadata & dependencies (uv compatible)
├── uv.lock             # Locked dependencies
├── .gitignore
└── README.md
```

## 🚀 Quick Start

### Prerequisites

- Python 3.10+
- [uv](https://github.com/astral-sh/uv) (recommended) or pip

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/Pawan-Chahar/TODO_API.git
   cd TODO_API
   ```

2. Install dependencies (using uv - fast & modern)

   ```bash
   uv sync
   ```

   Or with pip:

   ```bash
   pip install -r requirements.txt   # if you have one, otherwise create it
   ```

3. Run the API

   ```bash
   uv run python main.py
   # or
   python main.py
   ```

   The server will start at: **http://127.0.0.1:8000**

### Interactive Documentation

Open your browser and visit:

- **Swagger UI**: http://127.0.0.1:8000/docs
- **ReDoc**: http://127.0.0.1:8000/redoc

## 🔧 API Endpoints (Example)

| Method | Endpoint              | Description                     |
|--------|-----------------------|---------------------------------|
| GET    | `/todos`              | Get all todos                   |
| GET    | `/todos/{todo_id}`    | Get a single todo by ID         |
| POST   | `/todos`              | Create a new todo               |
| PUT    | `/todos/{todo_id}`    | Update a todo                   |
| DELETE | `/todos/{todo_id}`    | Delete a todo                   |

Request body example (JSON):

```json
{
  "title": "Buy groceries",
  "description": "Milk, bread, eggs",
  "completed": false
}
```

## 🛠️ Tech Stack

- **Framework**: FastAPI (ASGI, async, type-safe)
- **Dependency Management**: uv
- **Auto Docs**: FastAPI built-in OpenAPI + Swagger



## 📄 License

[MIT License](LICENSE) — feel free to use, modify, and distribute!

## 👨‍💻 Author

**Pawan Kumar Chahar**  
GitHub: [@Pawan-Chahar](https://github.com/Pawan-Chahar)  
Let's connect and build more cool projects! 🚀

---

⭐ Don't forget to star this repo if you find it helpful!
```

