structure of profiles:

config-repo/
├── common/                      # Shared global settings (all apps, all envs)
│   └── application.yml
├── inventory-service/           # Application-specific folder
│   ├── application.yml          # Defaults for inventory-service
│   ├── dev/
│   │   └── application.yml      # Dev overrides
│   ├── uat/
│   │   └── application.yml      # UAT overrides
│   └── prod/
│       └── application.yml      # Production overrides
└── order-service/               # Repeat for other services
