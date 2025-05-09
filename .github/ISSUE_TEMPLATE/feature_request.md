---
name: 🚀 Feature Request
description: Suggest a new feature or improvement
title: "[Feature] - "
labels: [enhancement]
assignees: []
---

<!--
🎯 Purpose: Collect clear, well-reasoned suggestions for improvements or new features.
-->

### 📘 Summary

<!-- Describe the feature you would like to see. -->
> Example: Add a "Remember Me" checkbox on the login page to keep users logged in.

---

### 💡 Motivation

<!-- Explain why this feature is important, what problem it solves, or how it improves the product. -->
> Users often complain about being logged out too quickly. This will improve user experience.

---

### 🧩 Proposed Solution

<!-- Suggest how it could be implemented. High-level ideas or UX thoughts. -->
- Add a checkbox in the login form labeled "Remember Me"
- Set a long-lived JWT or persistent session cookie if selected
- Store the preference on the client

---

### 🔁 Alternatives Considered

<!-- Did you think of any other approaches? Why did you reject them? -->
> Considered increasing session timeout, but it's less secure and affects all users.

---

### 🎯 Acceptance Criteria

<!-- Define clear conditions for when this feature is considered complete. -->
- [ ] A checkbox labeled "Remember Me" is present
- [ ] When checked, user stays logged in for 30 days
- [ ] When unchecked, session expires after 1 hour of inactivity

---

### 📎 Additional Context / Mockups

<!-- Link designs, external references, or relevant issues. -->
> Related to issue #42  
> Figma: https://www.figma.com/file/your-design


