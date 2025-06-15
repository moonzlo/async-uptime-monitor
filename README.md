├── app/
│   ├── main.py               # Entrypoint FastAPI
│   ├── api/                  # Роуты
│   ├── models/               # SQLAlchemy модели
│   ├── db/                   # Подключение и миграции
│   ├── services/             # Логика проверки сайтов
│   ├── celery_worker.py      # Celery запуск
│   └── config.py             # Настройки
├── tests/
│   ├── unit/
│   └── integration/
├── docker-compose.yml
├── Dockerfile
├── requirements.txt
├── README.md
└── .github/workflows/ci.yml
