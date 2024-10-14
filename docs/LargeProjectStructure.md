```
/myproject
│
├── go.work                <-- Go workspace file
│
├── services/              <-- Directory containing multiple services (each a module)
│   ├── service-a/
│   │   ├── go.mod         <-- Go module for service A
│   │   └── main.go        <-- Main file for service A
│   │
│   └── service-b/
│       ├── go.mod         <-- Go module for service B
│       └── main.go        <-- Main file for service B
│
├── shared/
│   ├── go.mod             <-- Go module for shared libraries
│   └── utils.go           <-- Shared utility Go file
│
└── infrastructure/
├── go.mod             <-- Go module for infrastructure code (optional)
└── infra.go           <-- Infrastructure setup code (e.g., DB, networking)
```