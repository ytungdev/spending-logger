# System Blueprint

## Overview
The project follows a **client-server architecture** where:
- **Frontend** handles UI & API calls
    - React
    - Svelte
    - Vue
- **Backend** processes requests & manages data
    - FastAPI
- **Database** stores user & expense records
    - SQLite/
    - PostgreSQL


## Architecture Diagram
[React Frontend] 
    |
[FastAPI Backend]
    |
[Database]


## API Data Flow Example
1. **User adds an expense** via React UI
2. **Frontend sends POST request** to `/expenses/`
3. **Backend validates & stores** the expense
4. **Frontend updates UI** with new expense