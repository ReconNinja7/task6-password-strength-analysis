# Task 6 – Password Strength Analysis

##  Overview
This task focuses on evaluating the strength of various passwords using the **Kaspersky Password Checker**.  
The goal is to understand what makes a password strong or weak, learn best practices, and explore common password attacks.

---

##  Screenshots
1. **Weak Password** – `password1_weak.png`  
2. **Medium Password** – `password2_medium.png`  
3. **Strong Password** – `password3_strong.png`  

---

##  Feedback from Evaluation

### 1️ Weak Password (`password1_weak.png`)
- Too short and simple.
- Uses only lowercase or predictable characters.
- Extremely easy to guess and vulnerable to brute force/dictionary attacks.

### 2️ Medium Password – `Apple@123` (`password2_medium.png`)
- Contains uppercase, lowercase, numbers, and a symbol.
- Appeared **71 times** in leaked password databases.
- Short in length and follows a predictable pattern.

### 3 Strong Password – `#ApP13!_NinJ@2025` (`password3_strong.png`)
- Contains uppercase, lowercase, numbers, and multiple symbols.
- No leaks found in public databases.
- Sufficient length for high security.

---

##  Best Practices for Creating Strong Passwords
1. **Use at least 12–16 characters** for better protection.
2. **Mix character types** – uppercase, lowercase, numbers, and symbols.
3. **Avoid dictionary words and common phrases**.
4. **Never use personal information** (birthdays, names, phone numbers).
5. **Use passphrases** made of random, unrelated words.
6. **Create unique passwords** for every account.
7. **Use a password manager** to generate and store passwords securely.

---

##  Tips Learned from Evaluation
- Strong passwords are longer, more complex, and not found in leak databases.
- Predictable patterns (like `word+number`) make passwords weak.
- Even if a password has symbols, if it’s in leaked lists, it’s unsafe.
- The combination of length and complexity dramatically increases security.

---

##  Common Password Attacks
- **Brute Force** – Tries every possible combination until the password is found.
- **Dictionary Attack** – Uses a list of common or leaked passwords to guess credentials.
- **Credential Stuffing** – Uses stolen username-password pairs on multiple platforms.
- **Phishing** – Tricks the user into entering credentials on a fake site.

---

##  How Password Complexity Affects Security
| Password Type        | Time to Crack (Approx.) |
|----------------------|-------------------------|
| Only lowercase, 6 characters | < 1 second |
| Mixed case + numbers, 8 characters | Few minutes |
| Mixed case + numbers + symbols, 12 characters | Centuries |
| Strong passphrase (16+ chars) | Practically impossible |

Increasing **length** exponentially increases the combinations an attacker must try.  
Adding **complexity** (symbols, numbers, mixed case) makes brute force and dictionary attacks ineffective.

---

## Author
**Md Farhan Hussain**  
*Cybersecurity Intern – Elevate Labs*

