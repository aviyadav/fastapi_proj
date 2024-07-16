# fastapi_proj

### Run- uvicorm main:app --port 9200 --reload


## GET - http://localhost:9200/

## POST - http://127.0.0.1:9200/product
<br>
payload ==
{
    "title": "Powder",
    "description": "Lavender",
    "inventory": 2
}

## GET - http://127.0.0.1:9200/product
list all products

## PUT - http://localhost:9200/update/2
update product with id 2
payload==
{
    "title": "Soap New wala",
    "description": "Lyril Soap Red",
    "inventory": 2
}

## DELETE - http://localhost:9200/delete/2
delete product with id 2
