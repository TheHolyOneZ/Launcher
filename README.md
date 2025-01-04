# Launcher
A launcher that can be used for LAN parties, private use, or small groups (mainly designed for private use because I was bored)

# Setting Up Your Node.js Project

This guide explains how to set up a Node.js project in the folder where `app.js` is located. It includes instructions to install dependencies and initialize the required files.

---

## Prerequisites

1. **Download and Install Node.js**:
   - Download Node.js from the [official website](https://nodejs.org/).
   - Install it on your system. (Make sure `node` and `npm` are added to your system's PATH.)

2. **Verify Installation**:
   - Open a terminal and run the following commands to check your installation:
     ```bash
     node -v
     npm -v
     ```
   - These commands should display the installed versions of Node.js and npm.

---

## Setting Up the Project

1. **Navigate to Your Project Folder**:
   - Open a terminal and navigate to the folder containing `app.js`:
     ```bash
     cd path/to/project
     ```

2. **Initialize the Project**:
   - Create a `package.json` file by running:
     ```bash
     npm init -y
     ```
   - This will generate a `package.json` file with default configurations.

3. **Install Dependencies**:
   - Install the `open` package (required by `app.js`):
     ```bash
     npm install open

     npm install express
     ```
   - This will create:
     - A `node_modules` folder (containing the installed packages)
     - A `package-lock.json` file (for dependency tracking)

---

