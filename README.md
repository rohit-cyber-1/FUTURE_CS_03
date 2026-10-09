# FUTURE_CS_03
Task 3 - API security risk analysis with Postman and OWASP API Top 10

# Task 3: API Security Risk Analysis

Cyber Security Internship - Future Interns (Track: CS)

## What I did
- Built a small, deliberately insecure practice API (Python Flask) and ran it locally
- Tested it with Postman: login, user data, updates, deletes, search and error handling
- Found 10 weaknesses and matched each to the OWASP API Security Top 10 (2023)
- Rated the risk of each finding and wrote recommended fixes

## Key findings
- Weak, guessable login token
- Any user's data readable by changing the ID
- Passwords and card numbers exposed in replies
- A user can make themselves admin
- Verbose errors leak internal details

## Files
- API security report (PDF)
- Postman screenshots
- fake_api.py (the practice API used for testing)

## Tools
Postman, Python, Flask, OWASP API Security Top 10

## Note
All testing was done on a practice API I built and ran on my own computer.
All data in it is invented. No real systems were tested.
