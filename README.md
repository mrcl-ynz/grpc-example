# gRPC Demo

Para levantar el ejemplo:

```
docker compose up -d
```

La API corre en el puerto `3000` y tiene dos rutas:

- `/personas/all`: Entrega todas las personas en la base de datos.
- `/personas?id=x`: Entrega los datos de la persona cuya `id` sea igual a `x`.  
