Invalid Username Bug Report

Overview
This repository contains a bug report for the Demo Web Shop login functionality.
The issue: users can log in with an invalid username, which is a security flaw.

Bug Details
Website: OrangeHRM
Module: Login
Severity: High
Type: Authentication Bug

Steps to Reproduce
1. Go to the login page.
2. Enter an invalid username and any password.
3. Click Login.

Actual Result: Login succeeds.
Expected Result: Login should fail with an error message.
Screenshot
invalid_username_login.png

Environment
Browser: Chrome / Firefox / Edge (latest)
OS: Windows / macOS / Linux

Recommendation
Fix username validation in login.
Prevent unauthorized access.
