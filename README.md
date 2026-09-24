# goit-js-hw-05

Homework assignment #5 from the [GoIT](https://goit.global/) JavaScript course. A set of four small exercises practicing array methods (`map`, `filter`, `toSorted`, `reduce`) on arrays of objects, using arrow functions throughout.

## 📋 About

Each task is implemented as a standalone arrow function that is called with sample user data, logging the result to the console:

- **Task 1** — `getUserNames(users)`: uses `map()` to extract an array of names from an array of user objects.
- **Task 2** — `getUsersWithFriend(users, friendName)`: uses `filter()` to find users whose `friends` list includes a given name.
- **Task 3** — `sortByDescendingFriendCount(users)`: uses `toSorted()` to return a new array of users sorted by number of friends, descending.
- **Task 4** — `getTotalBalanceByGender(users, gender)`: uses `filter()` and `reduce()` to sum the account balances of users matching a given gender.

## 🛠️ Tech Stack

- Vanilla JavaScript (ES modules, ES6+ array methods, arrow functions)
- HTML5

## 📁 Project Structure

```
goit-js-hw-05-main/
├── js/
│   ├── task-1.js    # Extract user names (map)
│   ├── task-2.js    # Filter users by friend (filter)
│   ├── task-3.js    # Sort users by friend count (toSorted)
│   └── task-4.js    # Sum balances by gender (filter + reduce)
├── .prettierrc.json   # Prettier configuration
└── index.html          # Loads all four task scripts as ES modules
```

## 🚀 Getting Started

Open `index.html` in a browser and check the browser console (DevTools) to see the logged results of each task.
