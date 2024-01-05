Инициализация зависимостей
```
go mod init github.com/EvgeniyBudaev/go-tcp-server-gg
```

Сборка
```
go build -v ./cmd/
```

Удаление неиспользуемых зависимостей
```
go mod tidy -v
```

Тестирование в терминале
```
telnet localhost 3000
```