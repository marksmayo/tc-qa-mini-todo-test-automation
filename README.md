# mini-todo-app


# 📝 Mini To-Do App – Test Automation Challenge

This is a simple HTML+JS To-Do app built for automation test candidates. It has basic features like adding, completing, and deleting tasks. Your challenge is to write automated tests for this app using JavaScript.

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/mini-todo-app.git
cd mini-todo-app
```

### 2. Run the App

You can run the app in two ways:

#### Option A – Open Directly

Just open the `index.html` file in your browser.

#### Option B – Run on Local Server (Recommended for Automation)

If you have Node.js installed:

```bash
npx serve
```

Or install globally:

```bash
npm install -g serve
serve .
```

Then go to: [http://localhost:3000](http://localhost:3000)

---

## ✅ App Features

- Add task
- Mark task as completed
- Delete task
- Tasks appear dynamically in a list

---

## 🎯 Automation Task

Your job is to write test automation for this app using JavaScript and your preferred tool (Cypress, Playwright, or WebdriverIO).

### 📋 What to Automate

1. Open the app
2. Add a new task 
3. Verify it appears in the list
4. Mark the task as completed and check `.completed` class is added
5. Delete the task and verify it's removed from the list


### 🔨 What We Expect

- Use **Page Object Model (POM)**
- Use at least one utility/helper function
- Clean, readable JavaScript
- Basic assertions
- README explaining how to run the test

### 💡 Bonus

- Good selector strategy
- Test reusability
- Good commit history
- Extra validations

---

## 🙌 Good Luck!

If you have any questions during the challenge, feel free to reach out.
