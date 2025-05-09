
# 🌐 Request Header Parser Microservice

This is a Node.js and Express-based microservice that parses request headers and returns information like the **IP address**, **language**, and **user-agent**. It is a project built as part of the [freeCodeCamp](https://www.freecodecamp.org/) Back End Development and APIs certification.

---

## 🚀 Features

* Parse the **IP address** of the client.
* Retrieve the **language** preferences from the request headers.
* Extract the **user-agent** software information.
* Handles invalid input gracefully.

---

## 🔗 Example API Endpoints

### ✅ `/api/whoami`

**Endpoint:**
`GET /api/whoami`


---

### ❌ Invalid Input

**Endpoint:**
`GET /api/invalid`

**Example Output:**

```json
{
  "error": "Invalid Input"
}
```

---

## 🛠️ How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/Hussain-Tinwala/Request-Header-Parser-Microservice.git
   ```

2. Navigate into the project folder:

   ```bash
   cd request-header-parser-microservice
   ```

3. Install the necessary dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   npm start
   ```

   The app will be running on `http://localhost:3000`.

---

## 🛠️ Built With

* **Node.js**: JavaScript runtime for building server-side applications.
* **Express.js**: Fast and minimalist web framework for Node.js.
* **HTML/CSS**: For the front-end user interface.
* [**freeCodeCamp Boilerplate**](https://github.com/freeCodeCamp/boilerplate-project-header-parser): The original boilerplate project.

---

## 🔗 Links

* [GitHub Repository](https://github.com/Hussain-Tinwala/Request-Header-Parser-Microservice.git)

---

## 📧 Contact

If you have any questions or suggestions, feel free to reach out!

---
