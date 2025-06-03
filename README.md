# Password-Strength-Analysis

tep 1: Create Multiple Passwords with Varying Complexity
| Password      | Description                                              |
| ------------- | -------------------------------------------------------- |
| `123456`      | Very weak: Only numbers, short                           |
| `password`    | Weak: Common word, lowercase only                        |
| `Password123` | Moderate: Uppercase, lowercase, numbers                  |
| `Pass@123`    | Stronger: Includes symbol                                |
| `!Qw7$kLmZ9`  | Very strong: Mixed character types, good length          |
| `Tr0ub4dor&3` | Very strong: Uncommon structure, complexity, and symbols |

Step 2: Use Different Character Types
   Each password includes different elements:
   | Password      | Uppercase | Lowercase | Numbers | Symbols | Length |
| ------------- | --------- | --------- | ------- | ------- | ------ |
| `123456`      | ❌         | ❌         | ✅       | ❌       | 6      |
| `password`    | ❌         | ✅         | ❌       | ❌       | 8      |
| `Password123` | ✅         | ✅         | ✅       | ❌       | 11     |
| `Pass@123`    | ✅         | ✅         | ✅       | ✅       | 8      |
| `!Qw7$kLmZ9`  | ✅         | ✅         | ✅       | ✅       | 10     |
| `Tr0ub4dor&3` | ✅         | ✅         | ✅       | ✅       | 12     |

Step 3: Test Password Strength Using Online Tool
Used password strength checker tools (e.g., HowSecureIsMyPassword.net or NordPass Password Strength Checker).

Step 4: Note Scores & Feedback
| Password      | Estimated Crack Time | Feedback                              |
| ------------- | -------------------- | ------------------------------------- |
| `123456`      | < 1 second           | Extremely weak. Common password.      |
| `password`    | < 1 second           | Dictionary word. Easily guessed.      |
| `Password123` | Few hours            | Predictable structure. Needs symbols. |
| `Pass@123`    | Few days             | Better. Consider longer password.     |
| `!Qw7$kLmZ9`  | Centuries            | Strong. High complexity.              |
| `Tr0ub4dor&3` | Thousands of years   | Very strong. Uncommon and complex.    |

Step 5: Identify Best Practices for Strong Passwords
Use a mix of uppercase, lowercase, numbers, and symbols.
Avoid common words, patterns, or names.
Longer passwords (12+ characters) are significantly more secure.
Use passphrases or random strings.
Don’t reuse passwords across sites.

Step 6: Tips Learned from the Evaluation
Short and simple = easily cracked.
Mixing types of characters improves strength.
Unique, unpredictable patterns are much better.
Length boosts strength exponentially.
Password managers help store complex passwords safely.

Step 7: Common Password Attacks
| Attack Type             | Description                                                                               |
| ----------------------- | ----------------------------------------------------------------------------------------- |
| **Brute Force**         | Tries all possible combinations. Time-consuming but effective for short/simple passwords. |
| **Dictionary Attack**   | Tries words from a predefined list (like “password”, “123456”, etc.). Fast and common.    |
| **Credential Stuffing** | Uses known passwords from leaks to try on multiple sites.                                 |
| **Phishing**            | Trick users into revealing passwords via fake websites or messages.                       |
| **Keylogging**          | Malicious software records keystrokes to capture passwords.                               |

Step 8: Summary – How Password Complexity Affects Security
High complexity passwords (longer, mixed characters, random) drastically increase time needed for brute-force attacks.
Low complexity passwords (short, dictionary words, no symbols) can be cracked in seconds.
Strong passwords reduce the success rate of both brute-force and dictionary attacks.
Complexity combined with length is the most powerful defense.

OUTCOME:
Password Strength Analysis:
  Simple passwords like 123456 or password were cracked instantly.
  Complex passwords like !Qw7$kLmZ9 and Tr0ub4dor&3 were estimated to take centuries to crack.

Impact of Complexity:
  Adding length, symbols, numbers, and mixed-case letters significantly improves password security.
  Each additional character exponentially increases protection against brute-force attacks.

Best Practices Identified:
  Use 12+ characters with mixed character types.
  Avoid dictionary words and predictable patterns.
  Prefer passphrases or randomly generated passwords.
  Never reuse passwords across accounts.

Types of Attacks Studied:
  Brute Force: Tries every combination.
  Dictionary Attack: Uses common passwords or words.
  Credential Stuffing: Reuses leaked passwords.
  Keylogging & Phishing: Captures credentials via malware or deception.

Tips Learned:
  Strong passwords resist automated and manual attacks.
  Use a password manager to store complex passwords safely.
  Periodically update passwords and monitor for breaches.
