# 🌐 Website Official Winnicode

Welcome to the official documentation for **Winnicode** APIs, designed to facilitate seamless access to news articles and other features of the Winnicode platform.

### 🌍 Website

- [Visit Winnicode Official](https://winnicode.com)

---

## 📑 API Documentation

Winnicode provides access to news and article data through its API. Below, you’ll find the available endpoints, usage details, and an example link for accessing API responses.

### 📘 API Endpoints News and Articles

#### 1. News and Articles API

- **Endpoint**:

```
`https://winnicode.com/api/berita/json/{api_key}`
```

#### 2. API Access Token

- **Example API Token**:

```
`fd8c60257a217ec139d70d62747e42081eea41aa0bf4e9414fc76ddf2083cfed`
```

---

## 🚀 Implementation

### Quick Links

- **[API JSON Data](https://winnicode.com/api/berita/json/fd8c60257a217ec139d70d62747e42081eea41aa0bf4e9414fc76ddf2083cfed)**
- **[Example Fetch Implementation](https://api-berita.winnicode.com)**

### 🔎 API Overview

| API Name          | Developer | API Link                                                       | Status | Authentication |
| ----------------- | --------- | -------------------------------------------------------------- | ------ | -------------- |
| News/Articles API | Margarets | [View on API](https://winnicode.com/api/berita/json/{api_key}) | ✅     | `true`         |
| Database Pengguna | Margarets | [View on API](https://winnicode.com/api/user/json/{api_key})   | ✅     | `true lanjut`  |

---

## 📄 Usage Example

Here’s an example of a fetch request to retrieve data from the Winnicode News API:

```javascript
fetch(
  "https://winnicode.com/api/berita/json/fd8c60257a217ec139d70d62747e42081eea41aa0bf4e9414fc76ddf2083cfed"
)
  .then((response) => response.json())
  .then((data) => console.log(data))
  .catch((error) => console.error("Error:", error));
```
