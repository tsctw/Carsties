## How to start
```docker compose up -d```

```dotnet watch```

## DB control
```dotnet ef migrations add "InitialCreate" -o Data/Migrations```

```dotnet ef database update```

```dotnet ef database drop```

