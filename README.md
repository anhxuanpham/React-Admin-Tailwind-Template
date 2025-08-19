
````markdown
# Elstar Template

Elstar is a modern React-based template for building web applications with flexibility and scalability in mind.

---

## 🚀 Installation

### Prerequisites
Before you begin with **Elstar**, make sure your development environment has the following tools installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Yarn](https://yarnpkg.com/) *(optional)*

Verify installation:
```bash
node -v
npm -v
yarn -v   # optional
````

---

## 📦 Folder Structure

After downloading and extracting the `.zip` file, you will find **4 main folders**:

### 1. `demo`

* The **main preview project**.
* Contains everything shown in the live demo.
* ⚠️ *For reference only. Not recommended for building your app.*

### 2. `starter`

* A **starter pack** for developers.
* Initializes the **basic project structure**.
* ✅ *Recommended package for development.*
* Copy this folder to your workspace and start building your app.

### 3. `documentation`

* Contains an `index.html` file.
* Redirects to our **online documentation**.

### 4. `legacy`

* **Legacy 1.0 version** built with **JavaScript + Create React App**.
* ⚠️ *Deprecated & no longer maintained.*
* Will be **removed in the next major update**.

---

## ⚙️ Setup & Installation

1. Navigate to the package you want to use (`starter` recommended):

```bash
cd starter
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

This will download and install all necessary dependencies into the `node_modules` folder.

---

## ▶️ Getting Started

Once dependencies are installed, you can start the development server:

```bash
npm run dev
# or
yarn dev
```

By default, the app will be available at:

👉 [http://localhost:5173](http://localhost:5173)

---

## 🛠️ Available Scripts

Inside your project, you can run the following scripts:

* **Start development server**

  ```bash
  npm run dev
  ```

  Runs the app in development mode with hot reload.

* **Build for production**

  ```bash
  npm run build
  ```

  Builds the app for production into the `dist` folder.

* **Preview production build**

  ```bash
  npm run preview
  ```

  Runs a local server to preview the production build.

* **Linting (optional)**

  ```bash
  npm run lint
  ```

  Runs ESLint to check for code quality issues.

---

## 📂 Project Structure (Starter Pack)

```
starter/
├── public/              # Static files
├── src/                 # Source code
│   ├── assets/          # Images, fonts, etc.
│   ├── components/      # Reusable UI components
│   ├── pages/           # Page-level components
│   ├── routes/          # Routing configuration
│   ├── services/        # API calls, utilities
│   ├── App.jsx          # Main app entry
│   └── main.jsx         # Application bootstrap
├── package.json
└── vite.config.js       # Vite configuration
```

---

## 🧩 Tech Stack

* [React](https://react.dev/)
* [Vite](https://vitejs.dev/)
* [Tailwind CSS](https://tailwindcss.com/) *(if included)*
* [React Router](https://reactrouter.com/)
* [ESLint](https://eslint.org/)

---

## ⚠️ Notes

* Use the `starter` package for development.
* The `demo` folder is for reference only.
* The `legacy` folder will be removed in future versions.

---

## 📖 Documentation

For detailed guides, please refer to our **online documentation** (linked via the `documentation/index.html` file).

```
```
