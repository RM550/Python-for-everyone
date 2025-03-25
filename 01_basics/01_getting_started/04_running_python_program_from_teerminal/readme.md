# 🐍 Running a Python Program from the Terminal

Running Python programs directly from the terminal is an essential skill for developers. This guide will walk you through running a Python script on **Windows**, **Mac**, and **Linux** in detail. 🚀

---

## ✅ Prerequisites
Before running Python programs, ensure you have the following:

1. **Python Installed**
   - Download and install Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
   - During installation on Windows, check the box **"Add Python to PATH"**.

2. **Verify Installation**
   - Open your terminal (Command Prompt, PowerShell, or Terminal on Mac/Linux) and type:
     ```sh
     python --version
     ```
   - If you see an output like `Python 3.x.x`, Python is installed correctly.
   - On Mac/Linux, you may need to use:
     ```sh
     python3 --version
     ```

---

## 🖥️ Running a Python Program on Windows

### Step 1: Open the Command Prompt or PowerShell
- Press `Win + R`, type **cmd** or **powershell**, and press `Enter`.
- Navigate to the folder containing your Python script using the `cd` command:
  ```sh
  cd path\to\your\script
  ```
  Example:
  ```sh
  cd C:\Users\YourName\Documents
  ```

### Step 2: Run the Python Script
- If Python is installed correctly, run the script using:
  ```sh
  python script.py
  ```
- If you have multiple Python versions installed, you might need:
  ```sh
  py script.py
  ```
- If `python` is not recognized, try `python3`:
  ```sh
  python3 script.py
  ```

### Example Output:
If your script `hello.py` contains:
```python
print("Hello from Python! 🐍")
```
Running `python hello.py` will output:
```
Hello from Python! 🐍
```

---

## 🍏 Running a Python Program on Mac & Linux

### Step 1: Open the Terminal
- On Mac, open **Terminal** from Applications or press `Cmd + Space`, type **Terminal**, and press `Enter`.
- On Linux, press `Ctrl + Alt + T` to open the terminal.

### Step 2: Navigate to the Script's Directory
Use the `cd` command to move to the folder containing your script:
```sh
cd /path/to/your/script
```
Example:
```sh
cd ~/Documents
```

### Step 3: Run the Python Script
- Run the script using:
  ```sh
  python3 script.py
  ```
- On some systems, `python` may refer to Python 2, so always use `python3` to avoid compatibility issues.

### Example Output:
If `hello.py` contains:
```python
print("Hello from Python! 🐍")
```
Running `python3 hello.py` will output:
```
Hello from Python! 🐍
```

---

## 🛠 Troubleshooting

🔹 **"Command not found" error?**
- Ensure Python is installed correctly by running `python --version` or `python3 --version`.
- On Windows, restart the system after installation if `python` is not recognized.
- On Mac/Linux, use `which python3` to verify the installation path.

🔹 **Script file not found?**
- Double-check that you're in the correct directory by running:
  ```sh
  ls  # Mac/Linux
  dir # Windows
  ```
- If your script is missing, ensure it's saved with the `.py` extension.

🔹 **Wrong Python version?**
- Use `python3` instead of `python` if needed.
- On Windows, try `py` instead of `python`.

---

## 🎯 Conclusion
You have now learned how to run a Python script from the terminal on **Windows, Mac, and Linux**! 🎉

Happy Coding! 💻🔥

