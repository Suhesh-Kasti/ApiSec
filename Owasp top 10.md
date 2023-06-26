## 1. Broken Object Level Authorization (BOLA)
- Most common API vulnarability
- It involves manipulating IDs to impersonate other users and access data

#### Risk exposure
1. Data loss
2. Disclosure
3. Data manipulation

#### Prevention
1. Define data access policies and implement access control
2. At application logic layer, enforce data access control. Should not enforce it in UI or API itself.
3. Implement automated testings to find flaws

## 2. Broken Authentication
- Missing security controls
- Poorly implemented controls

#### Risk exposure
1. Access to user's accounts
2. Data theft and unauthorized controls

#### Examples
- Weak passwords
- Brute-forcing ID/PW
- No captcha, rate limiting, lockouts
- Auth info in URLs
- No verifixationwhile chaning password
- Insecure password storage

#### Prevention
- Defining policies and standards
- Continuous testing

## 3.
