# 💻 UVISHA Coding Standards

## Purpose

This document defines the coding standards followed by every developer and AI Agent.

---

## General Rules

- Write readable code.
- Keep functions small.
- Avoid duplicate code.
- Use meaningful variable names.
- Add comments only when necessary.
- Never hardcode secrets.

---

## Naming Convention

Variables

camelCase

Functions

camelCase

Classes

PascalCase

Constants

UPPER_CASE

Folders

kebab-case

Files

kebab-case

---

## Error Handling

Always handle:

- API Errors
- Database Errors
- Validation Errors
- Network Errors

Never ignore exceptions.

---

## Logging

Every important action should be logged.

Never log passwords.

Never log tokens.

Never log API Keys.

---

## Documentation

Every public function should explain:

Purpose

Parameters

Return Value

---

## Security

Always validate input.

Always sanitize output.

Use prepared statements.

Use environment variables.

---

## Final Rule

Code should be understandable by another engineer five years later.