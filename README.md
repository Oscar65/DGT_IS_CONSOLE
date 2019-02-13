# DGT_IS_CONSOLE

Prueba técnica de IS en modo consola

Se me plantea diseñar una estructura de datos para la DGT que gestiona las infracciones y los puntos del carnet.

Esta aplicación está desarrollada en .NET C# sobre linux.

El desarrollo se ha hecho con dotnet y la base de datos con PosgreSQL.

Pasos para probar la aplicación:

1- Tener instalados los paquetes dotnet-runtime, dotnet-sdk, dotnet-host, nuget y postgresql

2- Tener arrancada la base de datos postgresql.

3- Crear la base de datos:

Tenemos que editar el fichero script_creacion_base_datos_y_usuario.sql y cambiar la contraseña.

luegoo ejecutar :

```
psql -U postgres -f script_creacion_base_datos_y_usuario.sql
```

Para ver la base detos entrar con el comando:

```
psql -U dgtuser -d dgtdb
```


Una vez creada la base de datos ejecutamos la aplicacion con el comando:

```
dotnet run Program.cs
```

Es una prueba muy simple que hice el primer día sin tener ninguna experiencia en .NET C#.


