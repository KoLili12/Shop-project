# Проект интернет-магазина

Проект содержит HTTP-сервер для отображения каталога товаров и административную панель для управления товарами.

## Шаги установки

1. **Клонирование репозитория (main ветка)**
   ```bash
   git clone -b main https://github.com/KoLili12/Shop-project.git
   cd Shop-project
   ```
2. **Установка зависимостей и запуск сервера**
   ```bash
   # Установка зависимостей сервера
   cd admin-server
   node index.js
   
   # Запуск сервера
   npm run dev
   ```

3. **Установка зависимостей и запуск клиентской части**
   ```bash
   # Установка зависимостей клиента
   cd product-server
   node index.js

4. **Доступ к приложению**
   - Клиентская часть: `http://localhost:3000`
   - API сервера: `http://localhost:5000/api`
   - Документация swagger: `http://localhost:8080/api-docs`

