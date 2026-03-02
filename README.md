# User API Specification

## Create User
Endpoint : POST /api/users

Request Body :

```json
{
  "nama" : "Maura Anindita Kirana",
  "usia" : 19
}
```

Response Body (success) :

```json
{
  "data": {
    "id" : "random string",
    "nama": "Maura Anindita Kirana",
    "usia": 19
  }
}
```

Response Body (failed) :

```json
{
  "error": "Invalid input data"
}
```

## Update User
Endpoint : PUT /api/users/{id}

Request Body :

```json
{
  "nama" : "Maura Anindita Kirana",
  "usia" : 19
}
```

Response Body (success) :

```json
{
  "data": {
    "id" : "random string",
    "nama": "Maura Anindita Kirana",
    "usia": 19
  }
}
```

Response Body (failed) :

```json
{
  "error": "User not found"
}
```

## Get User
Endpoint : GET /api/users

Response Body (success) :

```json
{
  "data": {
    "id" : "random string",
    "nama": "Maura Anindita Kirana",
    "usia": 19
  }
}
```

Response Body (failed) :

```json
{
  "error": "User not found"
}
```

## Delete User
Endpoint : DELETE /api/users/{id}

Response Body (success) :

```json
{
  "message": "User deleted successfully"
}
```

Response Body (failed) :

```json
{
  "error": "User not found"
}
```


Screenshot Hasil
<img width="1919" height="1079" alt="Screenshot 2026-03-02 111115" src="https://github.com/user-attachments/assets/8cee4a85-edd3-4aaf-965d-fb09f77a0ead" />

<img width="1919" height="1078" alt="Screenshot 2026-03-02 111128" src="https://github.com/user-attachments/assets/97da33f9-39f6-473f-854d-a665d6280fbb" />

<img width="1919" height="1079" alt="Screenshot 2026-03-02 111452" src="https://github.com/user-attachments/assets/a486206f-8882-4b33-8509-a9c3ca053423" />

