# 03 - Domain Model

## Entity: User

### Purpose

Stores user profile and authentication information.

### Attributes

| Attribute | Description |
|-----------|-------------|
| id | Unique identifier |
| fullName | User's full name |
| email | User's email address |
| passwordHash | Encrypted password |
| country | User's country |
| preferredCurrency | User's preferred currency |
| emailVerified | Indicates whether the email is verified |
| authenticationProvider | EMAIL or GOOGLE |
| createdAt | Account creation timestamp |
| updatedAt | Last updated timestamp |