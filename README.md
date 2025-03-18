1. Clone Project

```bash
git clone https://github.com/LongHoangABCD/project2
```

2. Install php briary

```bash
# create vendor
composer update
```

3. Install js briary

```bash
# create node_modules
npm i
```

4. Create .env file

-   Copy `.env.example` to `.env`
-   Config `.env` file

5. Create database

```bash
php artisan migrate
```

6. Create fake data

```bash
php artisan db:seed
```

7. Run project

```bash
npm run dev
php artisan serve
```

```bash
composer run dev
```
