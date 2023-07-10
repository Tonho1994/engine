

# Punto de Ventra - API

Llevar la contabilidad de un negocio restuarantero día a día.


## Autore

- [@Tonho1994](https://github.com/Tonho1994)
- [@Dadomon](https://github.com/Dadomon)


## Run Locally

Clone the project

```bash
  git clone git@github.com:Tonho1994/engine.git
```

Go to the project directory

```bash
  cd engine
```

Copy .env

```bash
  cp .env.example .env
```

Fill it with your database info

   `DB_DATABASE`=engine

   `DB_USERNAME`=tonho

   `DB_PASSWORD`=1234

Install Dependencies

```bash
  composer install
```

Start the server

```bash
  php artisan serve
```


## API Reference

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |
