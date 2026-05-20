

📘 Project Overview

This project automates the Login functionality of DemoQA using a Hybrid Test Automation Framework.

The framework combines:

- Selenium WebDriver

- PyTest Framework
  
- Page Object Model (POM)
  
- Data-Driven Testing
  
- HTML Reporting
  
- Logging
  
- Screenshot Capture

The main goal of this project is to build a reusable, maintainable, and scalable automation testing framework.

---

⚙️ Tools & Technologies Used

| Category | Tool / Library |

|---|---|

| Programming Language | Python |

| Automation Tool | Selenium WebDriver |

| Test Framework | PyTest |

| Design Pattern | Page Object Model (POM) |

| Framework Type | Hybrid Framework |

| Testing Type | Data-Driven Testing |

| Reporting | pytest-html |

| Browser | Google Chrome |

---

 📂 Folder Structure

```bash
DemoQA_Login_Automation/
│
├── base_pages/
│   └── login_page.py
│
├── test_cases/
│   └── test_login.py
│
├── test_data/
│   └── login_data.py
│
├── utilities/
│   └── logger.py
│
├── screenshots/
│
├── reports/
│   └── Report.html
│
├── conftest.py
│
├── requirements.txt
│
└── README.md
```

---

 ⚙️ Framework Features

✅ Page Object Model (POM)

✅ Data-Driven Testing

✅ PyTest Fixtures

✅ HTML Reporting

✅ Logging Support

✅ Screenshot Capture on Failure

✅ Reusable Components

✅ Scalable Framework Structure

---

⚙️ How The Framework Works

 1️⃣ Browser Setup

`conftest.py` handles browser initialization and teardown using PyTest fixtures.

---

2️⃣ Page Object Model (POM)

`login_page.py` contains:

- Web element locators
- Reusable methods
- Login actions

Example methods:
- Open Login Page
- Enter Username
- Enter Password
- Click Login

---

3️⃣ Data-Driven Testing

`login_data.py` stores multiple datasets such as:

- Valid credentials
  
- Invalid credentials
  
- Expected results

PyTest parameterization executes multiple test scenarios using the same test script.

---

4️⃣ Test Execution

`test_login.py` executes all login scenarios and validates results using assertions.

---

5️⃣ HTML Reporting

`pytest-html` automatically generates an HTML report after test execution.

The report contains:

- Pass/Fail status
  
- Execution summary
  
- Environment details
  
- Test logs
  
- Execution time

---

🧾 Why This Is a Hybrid Framework

This project is called a Hybrid Framework because it combines multiple automation approaches together:

- Page Object Model (POM)
  
- Data-Driven Testing
  
- PyTest Framework
  
- Reporting
  
- Logging
  
- Screenshot Handling

Combining multiple framework concepts into one project forms a Hybrid Automation Framework.

---

 ▶️ Installation

Clone The Repository

```bash
git clone https://github.com/ushaun01/demoqa-login-hybrid-framework.git
```

---

Install Dependencies

```bash
pip install -r requirements.txt
```

---

 ▶️ Run The Tests

Run All Test Cases

```bash
pytest -v -s
```

---

 Generate HTML Report

```bash
pytest --html=reports/Report.html
```

---

📊 Sample Test Scenarios

| Test Scenario | Expected Result |

|---|---|

| Valid Username + Valid Password | Login Success |

| Invalid Username | Error Message |

| Invalid Password | Error Message |

| Empty Username | Validation Message |

| Empty Password | Validation Message |

---

📌 Learning Outcomes

Through this project, I gained hands-on experience in:

- Selenium Automation Testing
  
- PyTest Framework
  
- Hybrid Framework Design
  
- Page Object Model (POM)
  
- Data-Driven Testing
  
- HTML Reporting
  
- Logging
  
- Screenshot Handling
  
- Test Case Structuring
  
- Framework Organization
  

---

👩‍💻 Author

 Usha Nazare

Mechanical Engineering Graduate transitioned into IT and passionate about Software Testing & Test Automation.


### Project Type:
Practice Automation Project
