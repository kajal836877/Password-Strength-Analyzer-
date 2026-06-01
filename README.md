# Password Strength Analyzer

A Java-based tool that evaluates the strength of user-entered passwords by checking length, complexity, and providing strength ratings.

## Features

- ✅ **Length Check**: Verifies password is at least 8 characters
- ✅ **Complexity Check**: Validates presence of:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special characters (!@#$%^&*, etc.)
- ✅ **Scoring System**: 0-5 point scale
- ✅ **Strength Rating**: Weak, Medium, or Strong

## How It Works

The analyzer assigns 1 point for each of the following:

| Criterion | Requirement | Points |
|-----------|-------------|--------|
| Length | ≥ 8 characters | +1 |
| Uppercase | At least 1 capital letter | +1 |
| Lowercase | At least 1 small letter | +1 |
| Number | At least 1 digit | +1 |
| Special Char | At least 1 special character | +1 |

### Strength Ratings

| Score | Rating |
|-------|--------|
| 0-2 | Weak 🔴 |
| 3-4 | Medium 🟡 |
| 5 | Strong 🟢 |

## Installation & Setup

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Terminal/Command Prompt

### Steps

1. **Save the code** as `PasswordStrengthAnalyzer.java`

2. **Compile** the program:
   ```bash
   javac PasswordStrengthAnalyzer.java
   ```

3. **Run** the program:
   ```bash
   java PasswordStrengthAnalyzer
   ```

## Usage

1. Run the program
2. Enter a password when prompted
3. View the score and strength rating

### Example
