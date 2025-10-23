# 🪜 Step 1: Environment Setup & Basic Foundation

**Goal:** Build your local setup to write, run, and manage Java-based automation projects.

---

## 🧩 1. Install Required Tools

| Tool | Purpose | Download Link |
|------|----------|---------------|
| **Java JDK (17 or 21)** | Language runtime for Java automation | [https://adoptium.net](https://adoptium.net) |
| **IntelliJ IDEA Community** | IDE to write and run Java code | [https://www.jetbrains.com/idea/download](https://www.jetbrains.com/idea/download) |
| **Apache Maven** | Build & dependency management tool | [https://maven.apache.org/download.cgi](https://maven.apache.org/download.cgi) |
| **Git** | Version control for saving project progress | [https://git-scm.com/downloads](https://git-scm.com/downloads) |
| **Google Chrome + ChromeDriver** | Browser and WebDriver for Selenium | [https://chromedriver.chromium.org/downloads](https://chromedriver.chromium.org/downloads) |

---

## ⚙️ 2. Verify Installation

### ✅ Check Java
```bash
$ java -version
openjdk version "17.0.2"
```

### ✅ Check Maven
```bash
$ mvn -version
# Example output:
Apache Maven 3.9.x
```

### ✅ Check Git
```bash
$ git --version
```

---

## 🧠 3. Setup IntelliJ Project (Your First Java Project)

01. **Open IntelliJ → New Project → Java → Maven Project**
02. GroupId: `com.foo`
    
    ArtifactId: `automation-learning`
03. Click **Finish**

### 📁 Project Structure
```bash
automation-learning/
 ├── src/
 │    ├── main/java/
 │    └── test/java/
 └── pom.xml
```

---

## 📦 4. Create Your First Java Class

**Path**: `src/main/java/com/foo/HelloWorld.java`
```java
package com.foo;

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Welcome to Automation Journey, Foo!");
    }
}
```

**Output:**
```console
Welcome to Automation Journey, Arpita!
```

---

## 🧰 5. Understand the Project Structure

| Folder       | Purpose           |
| -------------|------------------ |
| `main/java`  | Core automation code (pages, utilities) |
| `test/java`  | Test cases |
| `pom.xml`    | Maven dependency manager |
| `.gitignore` | Ignored files for Git |
| `README.md`  | Documentation for GitHub |

---

## 🧪 6. Initialize Git and Push to GitHub

01. Create a new empty repository on GitHub — name it automation-learning.
02. Inside your project terminal, run:
```bash
$ git init
$ git add .
$ git commit -m "Initial project setup"
$ git branch -M main
$ git remote add origin https://github.com/YourUsername/automation-learning.git
$ git push -u origin main
```

**✅ Now your basic setup is live on GitHub.**

---

## 💡 7. Outcome of Step 1

After completing this step, you will have:
- `Java` + `Maven` + `IntelliJ` correctly set up
- Your first `Java` program running
- Your project ready for automation learning
- Your GitHub repo initialized

---

## 📘 8. Next Step Preview (Step 2)

Next, you’ll learn **Java programming fundamentals for automation**, including:
- Data types, variables, and loops
- Methods and OOP basics
- Collections and exception handling
- Small daily practice programs

🟢 Next Section: Step 2 → Java Programming Foundation(Coming Next in the Roadmap)

---
