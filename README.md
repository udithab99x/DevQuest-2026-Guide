# DevQuest-2026-Guide

## Overview

DevQuest is an international hackathon organized under the tertiary category of CODEFEST, aimed at showcasing the unique talents, creativity, and innovations of undergraduates from universities and institutes worldwide.

## Getting Started

### 1. Setting Up Your Environment

Ensure you have the following installed:

- **Git**: Version control system
- **Node.js**: JavaScript runtime
- **npm**: Node package manager

Recommended: Use a Node Version Manager (NVM) for managing multiple Node.js versions.

**Clone the Project:**

```bash
git clone <repository-url>
```

**Install Dependencies:**

```bash
npm install
```

**Create Environment File:**

You need to create .env file relevent to the code

**Validate the Environment Setup:**

```

**Validate Setup:**

Run the sanity test:

```bash
npm test _sanity.test.js
```

### 2. Setting Up the Development Database

To set up the SQLite database:

```bash
npm run migrate
npm run seed
```

### 3. Building and Running the Application

Start the server:

```bash
npm start
```

Open `index.html` with Live Server in your browser.

### 4. Executing the Tests

Run the following command to execute all test cases and validate your setup:

```bash
npm test 
```

Run the following command to execute single test file:

Example test file

```bash
npm test challenge01.test.js
```

### 5. Version Control Best Practices

Create a `.gitignore` file with the following content:

```
node_modules/
```

Commit and push changes:

```bash
git add .
git commit -m "Add .gitignore"
git push
```

### 6. Collaborating with Your Team

Ensure all team members pull the latest changes:

```bash
git pull
```

---

## Challenges
-[Challenges](https://udithab99x.github.io/test-run-challenges-2026/)


---

## Additional Resources

- [DevQuest Official Website](https://codefest.lk/devquest/)

For any issues or support, contact the DevQuest team at **+94 72 862 73 20**.

