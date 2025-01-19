- **Описание**: Создает образ из Dockerfile.
- **Синтаксис**:
    
    `docker build [OPTIONS] PATH | URL | -`
    
- **Основные флаги**:
    
    - `-t` или `--tag`: Задает имя и тег образа (например, `my-image:latest`).
    - `--no-cache`: Не использовать кэш при сборке.
    
- **Пример использования**:

bash

`docker build -t my-image .` 