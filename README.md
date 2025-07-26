# DB Normalizer Pro

Welcome to **DB Normalizer Pro**! 🎓

This is a simple, interactive web tool I built as a college student to help myself (and others) understand and practice database normalization concepts. If you're learning about relational databases, candidate keys, or normal forms, this project is for you!

## 🚀 Features Implemented

- **Candidate Key Finder:**
  - Enter a schema and functional dependencies to automatically find all candidate keys.
- **Attribute Closure Calculator:**
  - Calculate the closure of a set of attributes with respect to the given functional dependencies.
- **Normalization Analysis:**
  - Analyze your schema for 1NF, 2NF, 3NF, and BCNF. Instantly see which normal forms are satisfied or violated.
- **Decomposition Guidance:**
  - If your schema doesn't meet a normal form, get step-by-step decomposition and see the resulting relations.
- **Modern, Student-Friendly UI:**
  - Clean, responsive interface using Bootstrap 5. Works great on laptops and phones.

## 📚 How to Use

1. **Download or clone this repo.**
2. **Open `index.html` in your browser.**
3. **Enter your schema** (comma-separated, e.g., `A,B,C`).
4. **Enter functional dependencies** (comma-separated, e.g., `AB->C,C->B`).
5. **Find Candidate Keys:** Click the button to display all candidate keys.
6. **Calculate Attribute Closure:** Enter attributes and calculate their closure.
7. **Analyze & Normalize:** Click to check normal forms and view decomposition steps if needed.

## 📝 Example

- **Schema:** `A,B,C`
- **Functional Dependencies:** `AB->C, C->B`

## 🛠️ Technologies Used
- HTML, CSS, JavaScript
- [Bootstrap 5](https://getbootstrap.com/)

---

*This project was created as part of my college coursework to help myself and others learn about database normalization. Feel free to fork, use, or contribute!* 😄 