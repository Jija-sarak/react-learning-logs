# react-learning-logs

# Jan 6, 2026

---

## 1. What is React?
- React is a **JavaScript library for building user interfaces (UI)**.
- It **automatically updates the UI** when data changes.
- React makes websites **dynamic and efficient** by updating **only the parts of the UI that need to change**.
- Example: When a user types, clicks, or submits a form, React updates the relevant part of the screen **without reloading the whole page**.

---

## 2. Why React is Better Than Plain JavaScript
**In plain JavaScript:**
- You have to **manually manipulate the DOM** to update elements.
- As the app grows, this can become **messy, slow, and error-prone**.

**With React:**
- You **describe what the UI should look like** for a given state.
- React **handles updates automatically** using its Virtual DOM.
- Only the **changed parts** of the UI are updated.
- This makes code **cleaner, predictable, maintainable, and scalable**.

---

## 3. React Apps Are Made of Components
- React is **component-based**, meaning everything on the screen comes from **small building blocks called components**.
- Each component handles a **small part of the UI** — e.g., a button, header, or list item.
- **Analogy:** Components are like **LEGO blocks** — reusable and fit together to make complex UIs.
- Components can be:
  - **Function Components** (modern, most common)
  - **Class Components** (older style)
- Components can use:
  - **Props** — data passed from parent to child (read-only)
  - **State** — internal data that can change over time
- Example: A webpage might include **Navbar**, **TodoList**, and **Footer** components.

---

## 4. Summary
- React is a **JavaScript library for building the visual parts of a webpage**.
- It lets you **use JavaScript logic to describe the UI**, and React efficiently updates the DOM.
- React is **built around components** — small, reusable blocks that together form the complete UI.
