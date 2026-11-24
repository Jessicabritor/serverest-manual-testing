# 👩🏻‍💻 ServeRest – Manual Testing: User Registration

Manual testing project for the user registration page of
[ServeRest](https://front.serverest.dev/cadastrarusuarios), a public practice
application. It includes a test plan, 28 executed test cases and a defect report
with video evidence.

## 📋 Overview
| Item | Details |
|------|---------|
| Application | ServeRest (public practice app) |
| Module | User registration |
| Type | Manual functional testing (UI) |
| Environment | Google Chrome 152, macOS, laptop |
| Test design techniques | Equivalence Partitioning, Boundary Value Analysis |

## 📊 Results
| Metric | Result |
|--------|--------|
| Test cases executed | 28 |
| Passed | 19 |
| Failed | 9 |
| Defects reported | 9 (1 high, 4 medium, 4 low) |

## 🔎 Key findings
- The system accepts names outside the 3–20 character range and names made only of spaces
- Passwords outside 8–20 characters, or without an uppercase letter, number or special character, are accepted
- **High severity:** an already registered e-mail can be used to create a new account

> The validation rules were defined from observation of the application, as no
> documentation was available (see the risks section of the test plan).

## 🎯 Scope
**In scope:** Name, E-mail and Password validation; regular and administrator
registration; duplicate e-mail; empty fields; Register button and redirection;
"Entrar" (Log in) link.

**Out of scope:** performance, security, other browsers and operating systems,
mobile devices, pages outside the registration flow.

## 📄 Documents
| Document | English | Português |
|----------|---------|-----------|
| Test Plan | [PDF](en/Test_Plan.pdf) | [PDF](pt/Plano_de_Teste.pdf) |
| Test Cases | [PDF](en/Test_Cases.pdf) | [PDF](pt/Casos_de_Teste.pdf) |
| Defect Report | [PDF](en/Defect_Report.pdf) | [PDF](pt/Relatorio_de_Defeitos.pdf) |

Excel versions are available in the same folders.

## 🛠️ Tools
Spreadsheets for documentation, Jam.dev for bug evidence recordings.

## ✍️ Author
Jéssica Brito – QA Tester | [LinkedIn](www.linkedin.com/in/jessicabritor)
