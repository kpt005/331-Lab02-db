
# 🗂️ 331-Lab02-db

>This folder contains a sample JSON database for use with tools like [json-server](https://github.com/typicode/json-server).

---

## 📄 Contents

- **`db.json`** — Contains a list of community events with details such as:
  - `id`, `category`, `title`, `description`, `location`, `date`, `time`, `petsAllowed`, `organizer`

---

## 🚀 Usage

You can use this file as a mock REST API using [json-server](https://github.com/typicode/json-server) or similar tools.

### ▶️ Run Locally with json-server

1. **Install json-server globally (if you haven't already):**
   ```sh
   npm install -g json-server
   ```
2. **Start the server:**
   ```sh
   json-server --watch db.json
   ```
3. **Access your events at:**
   [http://localhost:3000/events](http://localhost:3000/events)

---

### 🌐 Use the Free Online Mock API

You can also use [my-json-server.typicode.com](https://my-json-server.typicode.com/) to serve your `db.json` from a public GitHub repository:

1. Create a new **public** GitHub repository
2. Add your `db.json` file to the repository
3. Access your mock server at:
   ```
   https://my-json-server.typicode.com/[your-username]/[your-repo-name]/events
   ```

#### Example (My Mock API)

- [https://my-json-server.typicode.com/kpt005/331-Lab02-db/events](https://my-json-server.typicode.com/kpt005/331-Lab02-db/events)

---

## 📝 Notes

- This file does **not** support comments. If you need to add notes, use a custom field (e.g., `"_note"`).
- For more information, see the [json-server documentation](https://github.com/typicode/json-server).
