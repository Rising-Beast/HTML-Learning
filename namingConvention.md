# 🧠 Common Naming Conventions in Programming

Here are popular naming styles used in code, files, URLs, and constants:

---

## 🐫 1. camelCase
- **Description:** First word lowercase, next words capitalized.
- **Use Case:** Variables, functions (JavaScript, Java, etc.)
- **Example:**
  ```javascript
  let userName = "Ayush";
  function getUserInfo() {}
  ```

---

## 🐍 2. snake_case
- **Description:** All lowercase, words separated by underscores.
- **Use Case:** Python variables, database fields
- **Example:**
  ```python
  user_name = "Ayush"
  def get_user_info():
      pass
  ```

---

## 🐘 3. PascalCase
- **Also Known As:** UpperCamelCase
- **Description:** Every word starts with a capital letter.
- **Use Case:** Class names, React components
- **Example:**
  ```js
  class UserProfile {}
  const MyComponent = () => {}
  ```

---

## 📎 4. kebab-case
- **Description:** All lowercase, words separated by hyphens.
- **Use Case:** URLs, file names, CSS classes
- **Example:**
  ```html
  <div class="user-profile-card"></div>
  ```
  ```
  https://example.com/user-profile-card
  ```

---

## 🔤 5. UPPER_SNAKE_CASE
- **Description:** All caps with underscores between words.
- **Use Case:** Constants
- **Example:**
  ```c
  #define MAX_LENGTH 100
  const API_KEY = "XYZ123";
  ```

---

## 🧪 6. dot.case
- **Description:** Words separated by dots.
- **Use Case:** Config files or nested keys
- **Example:**
  ```json
  {
    "user.name": "Ayush"
  }
  ```

---

## ✅ SEO-Friendly Naming Summary

| Context        | Best Style     | SEO Impact |
|----------------|----------------|------------|
| URLs           | `kebab-case`   | ✅ High     |
| File Names     | `kebab-case`   | ✅ Medium   |
| Class/ID Names | semantic any   | ❌ Low      |
| JS Variables   | `camelCase`    | ❌ None     |

---

> 📝 Tip: Use consistent naming styles to improve code readability and maintainability!