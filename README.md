# Kanban TODO App - Full Stack Project

Dự án xây dựng ứng dụng quản lý công việc theo mô hình Kanban board với FastAPI backend và Vanilla JavaScript frontend.

## Cấu trúc dự án

```
kanban-todo-project/
├── kanban-todo-api/          # Backend (FastAPI)
├── kanban-frontend/          # Frontend (Vanilla JS)
├── docs/                     # Documentation
├── scripts/                  # Utility scripts
├── tests/                    # Integration & E2E tests
└── .github/workflows/        # CI/CD
```

## Công nghệ sử dụng

### Backend
- FastAPI (Python web framework)
- SQLAlchemy (ORM)
- Alembic (Database migrations)
- JWT Authentication
- SQLite/PostgreSQL

### Frontend
- Vanilla JavaScript (ES6+)
- HTML5 & CSS3
- SortableJS (Drag & Drop)
- Fetch API

## Quick Start

1. Setup Backend:
```bash
cd kanban-todo-api
python -m venv venv
source venv/bin/activate  # Linux/macOS
# venv\Scripts\activate   # Windows
pip install -r requirements.txt
uvicorn app.main:app --reload
```

2. Setup Frontend:
```bash
cd kanban-frontend
# Sử dụng Live Server extension trong VS Code
# hoặc python -m http.server 8080
```

## Nội dung học tập

- [ ] Buổi 1: Setup môi trường
- [ ] Buổi 2: Python basics + OOP Basics
- [ ] Buổi 3: Kanban analysis and API design
- [ ] Buổi 4: FastAPI implementation
- [ ] Buổi 5: Database integration
- [ ] Buổi 6: JWT authentication
- [ ] Buổi 7: Frontend development basics
- [ ] Buổi 8: Frontend development advanced
- [ ] Buổi 9: Deployment

## Đóng góp

Vui lòng đọc [CONTRIBUTING.md](CONTRIBUTING.md) để biết cách đóng góp cho dự án.

## License

Dự án này được cấp phép theo [MIT License](LICENSE).
