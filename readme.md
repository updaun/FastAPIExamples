## FastAPI Basic Examples

### FastAPI - The Complete Course 2024 (Beginner + Advanced)

### Run Server

```
cd Project3
```

```
uvicorn TodoApp.main:app --reload --host 0.0.0.0 --port 8000
```

### Alembic

```
alembic init alembic
```

```
alembic revision -m "message"
```

```
alembic upgrade c9fe87b0ac17
```

```
alembic downgrade -1
```
