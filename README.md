# Offline Budget Tracker

[![GitHub](https://img.shields.io/github/license/thompson-1657/professional_readme_generator?color=%230288d1)](LICENSE)

## Description

---

The Offline Budget Tracker is a progressive web application that allows a user to track their budget. The user is able to track their budget by logging transactions through adding funds or subtracting funds from their total budget.

The best part about this application is the user can continuously update changes to their budget whether they are online or offline. The use of a service-worker, caching and indexedDB allows the application to function regardless of network connection. This means the application can be used anywhere, anytime.

## Table of Contents

---

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [License](#license)
- [Questions](#questions)

## Installation

---

To install the Offline Budget Tracker application the user can start by cloning the application from the repository onto their local machine.

```
https://github.com/thompson-1657/offline_budget_tracker.git
```

Once cloned the user can run

```
npm install
```

in the terminal to install the package.json and the node modules. The Offline Budget Tracker can then be run in the terminal command line by entering

```
node server.js
```

## Usage

---

[![recording (1)](https://user-images.githubusercontent.com/71091515/111894532-4ac0f400-89d9-11eb-9352-a62e9409e1b0.gif)](https://drive.google.com/file/d/16kkLxpNBOaW_Jg1HDG3IwQ0UhR4oTrct/view)

Click gif above to link to the full usage video.

To use this application the user can start by entering the name of a transaction as well as an amount. If the type of transaction is a deposit the user can the click " + Add Funds" and the transaction amount will be added to the total. At this time the transaction and amount will be logged below along with a graph of the budget overtime as transactions are entered.

If the user is entering a transaction that withdrawls funds they will click " - Subtract Funds" after entering the transaction name and amount. The total and graph will update accordingly.

If the user loses internet connection or turns on airplane mode they are still able to use the entire functionality of the application because this is a progressive web application. The user experience will not suffer due to connectivity.

## Technologies

---

- HTML5
- CSS3
- JavaScript
- Bootstrap
- Node.js
- Mongoose
- IndexedDB
- Heroku

## License

---

[MIT License](LICENSE)

## Questions

---

If you have any questions regarding the functionality or use of this application feel free to contact me via the information below.

GitHub: [thompson-1657](https://github.com/thompson-1657)

Email: thompson.1657@gmail.com
