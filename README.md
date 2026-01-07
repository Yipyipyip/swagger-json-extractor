# Swagger UI: Extract Endpoint JSON

A powerful Tampermonkey script that injects a **"Copy OpenAPI JSON"** button into any Swagger UI / FastAPI documentation.

## 🚀 Features

* **🎯 Partial Extraction:** Extracts only the **specific endpoint** you need right now.
* **🔄 Recursive Resolution:** Automatically resolves all `$ref` dependencies (Schemas, Enums, Models) recursively and includes them in the JSON. The result is a fully valid, standalone OpenAPI snippet.
* **🎨 Native Look:** Clones the styling of the existing "Try it out" button for perfect integration (Dark Mode & Light Mode compatible).
* **🔒 Fallbacks:** Works even if `window.ui` is blocked by a sandbox (scans scripts and headers).

## Installation

1. Install the [Tampermonkey](https://www.tampermonkey.net/) browser extension.
2. **[Click here to install the script](https://raw.githubusercontent.com/Yipyipyip/swagger-json-extractor/main/swagger-extractor.user.js)**.
3. Confirm the installation in Tampermonkey.

## 🛠 Usage

1. Open any Swagger UI page (e.g., your local FastAPI docs or the [Petstore](https://petstore.swagger.io/)).
2. Expand an endpoint.
3. Click the new **"Copy OpenAPI JSON"** button (located next to "Try it out").
4. The JSON for that endpoint and all its dependencies is now in your clipboard.

## 🤝 Contributing

Found a bug? Feel free to open an issue or submit a pull request.

## 📄 License

MIT License
