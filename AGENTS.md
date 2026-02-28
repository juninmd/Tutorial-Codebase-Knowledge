```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the development of robust, maintainable, and efficient AI coding agents. Strict adherence to these principles will be crucial for delivering high-quality code.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent should have a single, well-defined purpose. Avoid creating redundant code or functionality across multiple agents.
*   **Abstraction:** Use abstractions to represent common patterns and reusable components. Document these abstractions clearly.
*   **Code Reuse:**  Design agents to be easily modifiable and adaptable to new requirements.
*   **Minimize Code Blocks:** Keep code blocks concise and focused on a single task.

## 2. KISS (Keep It Simple, Stupid)

*   **Simplicity:**  Strive for the simplest solution that meets the requirements. Avoid unnecessary complexity.
*   **Readability:**  Prioritize clear and understandable code. Use meaningful variable names, comments, and formatting.
*   **Maintainability:**  Design code in a way that is easy to understand and modify in the future.

## 3. SOLID Principles

*   **Single Responsibility Principle (Again):**  Each class/agent should have only one reason to change.
*   **Open/Closed Principle:** The agent's behavior should be extensible through interfaces or abstract classes, without modifying the core logic.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace all their derived types without breaking the code.
*   **Interface Segregation Principle:** Clients should not be forced to provide data they do not use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Features:** Do not implement features or functionality that are not currently required.
*   **Focus on Requirements:** Prioritize implementing only what is explicitly stated in the requirements specification.
*   **Refactor Only When Necessary:** Refactoring should be driven by business value or technical debt, not by the desire to add new features.

## 5. Code Length & Structure

*   **Maximum Code Length:** 180 lines of code.  All code must be within this limit.
*   **Indentation:**  Use consistent and appropriate indentation (2 spaces).
*   **Line Length:** Maximum 120 characters per line.
*   **Whitespace:** Consistent whitespace around operators, keywords, and whitespace.

## 6. Test Coverage

*   **Minimum 80% Coverage:** All code must be covered by at least 80% of unit tests.  Automated test suites should be in place.
*   **Test-Driven Development:**  Writing tests *before* writing the code.
*   **Isolation:** Each test case should be independent of other test cases.

## 7. Development Workflow

*   **Code Reviews:** All new code must be reviewed by at least one other developer.
*   **Unit Tests:** Comprehensive unit tests are crucial for verifying the correctness of individual agents and functions.
*   **Integration Tests:**  Integration tests are needed to verify the interaction between agents.
*   **Version Control:** All changes should be committed to the version control system (e.g., Git).

## 8. Data Handling

*   **Mocking & Faking:**  Mocks and fakes should *only* be used for testing.  No real data or dependencies should be used in production.
*   **Test Data:**  Test data should be carefully managed and isolated.

## 9. File Structure

*   **Modular Structure:** Organize code into logical modules/agents.
*   **Clear Naming Conventions:** Use descriptive names for files, functions, and variables.
*   **Document Everything:** Provide clear comments explaining the purpose and logic of each element.

## 10. Tooling & Environment

*   **IDE:** Utilize a robust IDE (e.g., VS Code, PyCharm) with good code formatting and linting support.
*   **Linting:**  Enforce code style and potential errors using a linter (e.g., Black, ESLint).
*   **Static Analysis:** Employ static analysis tools to identify potential issues early in the development process.

## 11.  Documentation Requirements

*   **README:** A README file explaining the purpose, usage, and key concepts of the AGENTS.md file.
*   **API Documentation (Optional):**  For complex agents, consider API documentation to make them more accessible.
```