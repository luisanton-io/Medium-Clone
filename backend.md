# Medium

## Article

### METHODS

- GET search by title or content , filter by category
- GET single article
- POST article
- PUT update article
- DELETE article

```json
{
  "_id": "string", // server generated
  "headLine": "string",
  "subHead": "string",
  "content": "string",
  "author": "id",
  "cover": "string",
  "createdAt": Date, // server generated
  "updatedAt": Date // server generated
}
```

## Review

### METHODS

- GET
- GET
- POST
- PUT
- DELETE

```json
{
  "_id": "string", // server generated
  "elementId": "string",
  "text": "string",
  "claps": number, // one person can clap one time.
  "user": "id",
  "createdAt": Date, // server generated
  "updatedAt": Date // server generated
}
```

## Categories

### METHODS

- GET
- GET
- POST
- PUT
- DELETE

```json
{
  "_id": "string", // server generated
  "name": "string",
  "createdAt": Date, // server generated
  "updatedAt": Date // server generated
}
```
