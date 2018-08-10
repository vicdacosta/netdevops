```
inventory
├── group_vars
│   ├── core
│   │   └── .gitkeep
│   ├── remote
│   │   └── .gitkeep
│   ├── site1
│   │   └── .gitkeep
│   └── site2
│       └── .gitkeep
├── host_vars
│   ├── core1
│   │   └── .gitkeep
│   ├── core2
│   │   └── .gitkeep
│   ├── remote1
│   │   └── .gitkeep
│   └── remote2
│       └── .gitkeep
└── hosts.yaml
tests
├── main.yaml
├── playbooks
│   ├── core
│   │   └── main.yaml
│   ├── main.yaml
│   ├── remote
│   │   └── main.yaml
│   ├── site1
│   │   └── main.yaml
│   └── site2
│       └── main.yaml
└── roles
    ├── core
    │   ├── defaults
    │   │   └── main.yaml
    │   ├── meta
    │   │   └── main.yaml
    │   ├── tasks
    │   │   └── main.yaml
    │   ├── templates
    │   │   └── main.yaml
    │   └── vars
    │       └── main.yaml
    ├── remote
    │   ├── defaults
    │   │   └── main.yaml
    │   ├── meta
    │   │   └── main.yaml
    │   ├── tasks
    │   │   └── main.yaml
    │   ├── templates
    │   │   └── main.yaml
    │   └── vars
    │       └── main.yaml
    ├── site1
    │   ├── defaults
    │   │   └── main.yaml
    │   ├── meta
    │   │   └── main.yaml
    │   ├── tasks
    │   │   └── main.yaml
    │   ├── templates
    │   │   └── main.yaml
    │   └── vars
    │       └── main.yaml
    └── site2
        ├── defaults
        │   └── main.yaml
        ├── meta
        │   └── main.yaml
        ├── tasks
        │   └── main.yaml
        ├── templates
        │   └── main.yaml
        └── vars
            └── main.yaml
```
40 directories, 35 files
