# 🧾 Commit Message Cheatsheet (For MERN Developers)

### 🔹 **Basic Format**

    <type>: <short, clear summary>

Example:

    feat: add product filtering by category

------------------------------------------------------------------------

## 📘 Common `<type>` Keywords

  Type           Used For
  -------------- --------------------------------------------------------
  **feat**       Adding a new feature
  **fix**        Fixing a bug
  **refactor**   Changing code structure without changing behavior
  **style**      Formatting, spaces, semicolons, etc. (no logic change)
  **docs**       Documentation changes
  **test**       Adding or modifying tests
  **chore**      Maintenance stuff (configs, dependencies, etc.)
  **wip**        Work in progress (temporary, not finished yet)

------------------------------------------------------------------------

## 🧩 Commit Types & Examples

### 🟢 **feat** → new feature or functionality

    feat: add user authentication with JWT
    feat: implement dark mode toggle
    feat: create banner upload API
    feat: add product search functionality
    feat: add pagination to blog list

### 🔵 **fix** → bug or issue resolved

    fix: wrong route path in product API
    fix: missing dependency in package.json
    fix: image upload not saving to Cloudinary
    fix: incorrect state update in React useEffect
    fix: crash when user not logged in

### 🟠 **refactor** → code improvement (no feature/bug change)

    refactor: simplify cart reducer logic
    refactor: move constants to separate file
    refactor: clean up useEffect dependencies
    refactor: extract API calls into separate utils

### 🟣 **style** → visual or formatting-only change

    style: update button hover effect
    style: format code using prettier
    style: adjust spacing in product card
    style: fix indentation in Navbar component

### 🟡 **docs** → documentation updates

    docs: update README with installation steps
    docs: add API usage instructions
    docs: write comments for productController.js
    docs: add note about environment variables

### 🔴 **test** → adding or updating tests

    test: add unit tests for login function
    test: update snapshot for ProductList component

### ⚫ **chore** → maintenance tasks (configs, deps, etc.)

    chore: update dependencies
    chore: setup ESLint and Prettier
    chore: configure dotenv for environment variables
    chore: add gitignore for node_modules

### ⚪ **wip / temp / savepoint** → temporary commits or progress saving

    wip: half-done cart logic
    wip: implementing payment gateway integration
    savepoint: checkpoint before refactoring routes
    temp: push before switching branch

------------------------------------------------------------------------

## 🧠 Pro Tips

✅ **Start with lowercase** (except when naming specific components)\
✅ Keep summary short --- ideally **under 50 characters**\
✅ Use **imperative mood** --- e.g. "add", "fix", not "added", "fixed"\
✅ If you need more detail, add a blank line, then explain:

    feat: add product sorting feature

    Added sorting by price, name, and rating in the product list page.

✅ You can group multiple related changes:

    fix: handle null data in profile + add loading state

------------------------------------------------------------------------

## 💼 Example Flow (Real Scenario)

Let's say you're building a product upload form.

**Commits might look like:**

    feat: create product upload form UI
    feat: connect form to backend API
    fix: image upload not saving to Cloudinary
    refactor: extract image upload logic to utils
    style: improve form spacing and button color
    docs: add usage instructions in README

------------------------------------------------------------------------

Looks neat and professional 😄
