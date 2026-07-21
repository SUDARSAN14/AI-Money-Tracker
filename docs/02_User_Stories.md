# 02 - User Stories

## Epic 1: User Authentication

### User Story 1 - Register using Email

**Story ID:** US-001

**As a** new user,  
**I want** to create an account using my email address and password,  
**So that** I can securely access AI Money Tracker.

### Acceptance Criteria

- User can enter Full Name.
- User can enter a unique Email Address.
- User can create and confirm a password.
- User selects Country.
- User selects Preferred Currency.
- Registration succeeds only when all mandatory fields are valid.
- Verification email is sent after successful registration.
- User can log in only after verifying the email address.

---

### User Story 2 - Register using Google

**Story ID:** US-002

**As a** new user,  
**I want** to register using my Google account,  
**So that** I can quickly access AI Money Tracker without creating a separate password.

### Acceptance Criteria

- User can authenticate using a Google account.
- A new account is created if one does not already exist.
- Existing users are logged in automatically.
- User is redirected to the dashboard after successful authentication.
- User can set a password later from the Security Settings page if they want to use Email + Password login.