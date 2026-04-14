# Registration Module - Manual Testing Project

# Project Overview
This project focuses on the comprehensive manual testing of a user registration module. The primary goal was to verify functional requirements, validate input fields, and ensure a high-quality user experience by identifying critical bugs and usability issues.

# Testing Types Applied
* **Functional Testing:** To ensure all registration features work as expected.
* **Validation Testing:** To verify constraints for input fields like Name, Email, and Password.
* **UI/UX Testing:** To detect layout issues and ensure a responsive interface.
* **Negative Testing:** Testing with invalid data to evaluate system error handling.

# Key Bugs Discovered
Several **High Priority (A)** bugs were identified during the testing phase:
1.  **Field Validation:** First Name field accepts numeric values and special characters (e.g., Ahmed@120).
2.  **Boundary Value:** First Name field accepts excessively long inputs (up to 50 characters), exceeding requirements.
3.  **Format Validation:** Registration succeeds with invalid email formats, and the system fails to trigger validation errors.

# Environment
* **Browser:** Google Chrome (Latest Version)
* **OS:** Windows 10/11
* **Device:** Desktop

# Tools Used
* **Microsoft Excel:** For documenting Test Cases and Bug Reports.
* **Chrome DevTools:** For technical verification.
* **GitHub:** For project documentation and portfolio hosting.

# Project Deliverables
* **Test Case Suite:** Detailed steps for positive and negative scenarios.
* **Bug Report Ledger:** Comprehensive logs for all identified issues including Actual vs. Expected results.
