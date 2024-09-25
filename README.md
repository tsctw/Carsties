## How to start
```docker compose up -d```

```dotnet watch```

## DB control
```dotnet ef migrations add "InitialCreate" -o Data/Migrations```

```dotnet ef database update```

```dotnet ef database drop```

## Create a new Service
```dotnet new webapi -o src/MyService -controllers```

## Create a new class
```dotnet new classlib -o src/MyClass```

## Add the Service to Solution Explorer
```dotnet sln add src/MyService```

## List docker volumn 
```docker volume list```

## Remove docker volumn
```docker volume rm [volumnName]```