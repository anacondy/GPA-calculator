# Security Policy

## Security Features

This repository implements several security measures to ensure safe usage:

### 1. Content Security Policy (CSP)
- Implements CSP headers to prevent XSS attacks
- Restricts script and style sources

### 2. Input Validation
- All user inputs are validated before processing
- Numeric inputs are checked for valid ranges
- Subject names are sanitized and limited in length

### 3. XSS Protection
- Input sanitization using safe DOM methods
- No direct HTML injection via innerHTML
- All user content is escaped before rendering

### 4. Data Validation
- Prevents negative marks
- Ensures obtained marks don't exceed total marks
- Validates non-zero denominators

## Reporting a Vulnerability

If you discover a security vulnerability, please report it by:

1. **DO NOT** open a public issue
2. Email the repository owner directly
3. Provide detailed information about the vulnerability
4. Allow reasonable time for the issue to be addressed

## Security Best Practices for Users

1. Use the latest version of the application
2. Keep your browser updated
3. Don't enter sensitive personal information
4. Use HTTPS when accessing the deployed version

## Recent Security Updates

- **2024-10**: Implemented CSP headers
- **2024-10**: Added input sanitization
- **2024-10**: Enhanced validation for all inputs
- **2024-10**: Replaced innerHTML with safe DOM methods
