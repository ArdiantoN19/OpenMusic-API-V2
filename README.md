# Notes-API

OpenMusic API V2 - Hapi JS

```
    ### Endpont Registrasi dan Autentikasi
    - /users -> Untuk menambahkan pengguna/login
        body = {
            username: string,
            password: string,
            fullname: string
        },
        headers: {
            Authorizations: Bearer {token}
        },
        response: {
            status: 'success',
            data: {
                userId: "user_id"
            }
        }
```
