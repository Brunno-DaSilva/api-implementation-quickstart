# API Implementation Quickstart

A TypeScript, Node.js, C#, and Python to help developers quickly integrate with Capture & Direct APIs.

## 🚀 Supported languages & 🧰 Tech Stack

- **Node.js** (`node/`)
- **TypeScript** (`ts/`)
- **Python** (`python/`)
- **C# / .NET** (`csharp/`)
- **Postman Collection** (`postman/`)
- Axios (for HTTP requests)
- Dotenv (for environment variable support)
- Crypto (for HMAC signatures)
- File system utilities

---

## 📁 Folder Structure

```bash
api-implementation-quickstart/
├── README.md
├── .gitignore
├── node/                      # Node.js implementation
├── ts/                        # TypeScript implementation
│   ├── src/
│   │   ├── utils/
│   │   ├── types/
│   │   ├── start.ts
│   │   ├── get-results.ts
│   │   └── ...other endpoints
│   ├── config/
│   │   └── .env
│   ├── package.json
│   ├── tsconfig.json
│   └── ...
├── python/                    # Python implementation
│   ├── start.py
│   ├── get_results.py
│   ├── .env
│   └── requirements.txt
├── csharp/                    # C# implementation
│   ├── CaptureApiQuickstart.sln
│   ├── Program.cs
│   └── ... (organized by endpoint or feature)
├── shared-assets/            # Optional: shared diagrams, payload examples, etc.
│   ├── sample-payloads/
│   └── architecture.png
└── LICENSE
```

## 📄 License

MIT — feel free to fork and use for your own integrations.
