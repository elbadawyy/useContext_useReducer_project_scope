# ⚛️ React useContext + useReducer Practice Projects  

A collection of **10 small React projects** that demonstrate how to combine **useContext** and **useReducer** for global state management.  
These projects are lightweight but cover real-world use cases like authentication, todo management, theming, and more.  

---

### 🔹 1. Theme Switcher (Light / Dark Mode) 
**useReducer: Manage theme state (light, dark).**

**useContext: Provide theme state globally to all components.**

**Scope:**
 - Toggle between light & dark mode.  
 - Save preference in `localStorage`.  
 - Apply theme globally across components.  

---

### 🔹 2. Todo App with Filters  
**useReducer: Handle actions like ADD_TODO, TOGGLE_TODO, REMOVE_TODO, SET_FILTER**

**useContext: Share todos and filter state with all components.**

**Scope:**
 - Add, remove, and toggle todos.  
 - Filter: `All | Active | Completed`.  
 - Global state shared across `TodoList`, `TodoItem`, and `Filter`.  

---

### 🔹 3. Shopping Cart 🛒  
**useReducer: Actions for ADD_ITEM, REMOVE_ITEM, INCREASE_QTY, DECREASE_QTY**

**useContext: Share cart state across ProductList, Cart, and Navbar.**

**Scope:**
 - Add/Remove products to cart.  
 - Increase/Decrease quantity.  
 - Show cart count in Navbar & calculate total price.  

---

### 🔹 4. Authentication System (Basic)
**useReducer: Actions like LOGIN, LOGOUT, REGISTER**

**useContext: Provide auth state globally.**

**Scope:**
 - Login, Logout, Register with global state.  
 - Show logged-in user in Navbar.  
 - Simple protected route handling.  

---

### 🔹 5. Notes App with Categories  
**useReducer: Actions like ADD_NOTE, DELETE_NOTE, SET_CATEGORY**

**useContext: Share notes + category across components.**

**Scope:**
 - Add notes with category (Work, Personal, etc.).  
 - Filter notes by category.  
 - Delete note functionality with persistence.  

---

### 🔹 6. Multi-Step Form (Wizard Form)  
**useReducer: Actions like NEXT_STEP, PREVIOUS_STEP, UPDATE_FIELD.**

**useContext: Share form data & current step across all form components.**

**Scope:**
 - Multi-step form (Personal Info → Address → Review).  
 - Navigate between steps.  
 - Collect all data in global state before submission.  

---

### 🔹 7. Expense Tracker 💰  
**useReducer: Actions like ADD_EXPENSE, DELETE_EXPENSE, FILTER_BY_CATEGORY.**

**useContext: Share balance, expenses, and filters globally.**

**Scope:**
- Add expenses with amount & category.  
- Show total spent & remaining balance.  
- Filter by category and delete entries.  

---

### 🔹 8. Quiz App  
**useReducer: Actions like ANSWER_QUESTION, NEXT_QUESTION, RESET_QUIZ.**

**useContext: Share current question & score globally.**

**Scope:**
- Answer multiple-choice questions.  
- Track score globally.  
- Show results at the end.  

---

### 🔹 9. Notification System 🔔  
**useReducer: Actions like ADD_NOTIFICATION, REMOVE_NOTIFICATION.**

**useContext: Share notifications globally (accessible in Navbar, Sidebar, etc.).**

**Scope:**
- Add notifications globally (success, error, info).  
- Auto-dismiss after a few seconds.  
- Display notifications anywhere in the app.  

---

### 🔹 10. Playlist Manager 🎵 
**useReducer: Actions like ADD_SONG, REMOVE_SONG, PLAY_SONG, PAUSE_SONG.**

**useContext: Share playlist & current song globally.**

**Scope:**
- Add/remove songs from a playlist.  
- Mark currently playing song.  
- Simple player controls (Play/Pause).  

---

## 🛠️ Tech Stack  
- **React.js** (with Hooks)  
- **useContext** for global state sharing  
- **useReducer** for action-based state management  
- **Material UI / Tailwind CSS** *(for styling)*  

---


## 🙋‍♂️ Author

Made with ❤️ by Tanmay Shil
GitHub: [@TanmayShil](https://github.com/TanmayShil)
