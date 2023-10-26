# About k3d

Это легковесный кубер на основе k3s на докер контейнерах.

Установка:

```bash
wget -q -O - https://raw.githubusercontent.com/k3d-io/k3d/main/install.sh | bash
```

Запуск кластера:
```bash
k3d cluster create itmo
```

Утилита k3s автоматически пропишет конфигурацию подключения к кластеру в kubectl конфиг.
