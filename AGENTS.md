```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the quality, maintainability, and efficiency of all AGENTS.md files within this repository. Adherence to these principles is mandatory for all development activities.

**1. DRY (Don't Repeat Yourself)**

*   **Module Reuse:** Modules should be self-contained, performing a single, well-defined task. Avoid creating duplicated code across multiple files.
*   **Function Reuse:** Utilize functions and reusable components to minimize boilerplate and enhance code consistency.
*   **Template Definitions:** Employ templates for common structures (e.g., data structures, configuration files) to avoid repetition.

**2. KISS (Keep It Simple, Stupid)**

*   **Code Clarity:** Prioritize readability and understandable logic. Favor straightforward solutions over complex ones, unless demonstrable complexity provides a significant benefit.
*   **Minimize Complexity:** Keep functions and classes as small and focused as possible.
*   **Explain Code:** Add comments where necessary to clarify the purpose and logic behind code blocks, especially for non-obvious operations.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class or module should have a single, well-defined responsibility.
*   **Open/Closed Principle:**  The system should be extensible without modifying its core implementation.  New features should be added as new classes/modules.
*   **Liskov Substitution Principle:** Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be required to depend on implementation details of abstractions.
*   **Dependency Inversion Principle:** Interfaces should be preferred over concrete implementations.

**4. YAGNI (You Aren't Gonna Need It)**

*   **Avoid Unnecessary Features:** Resist the temptation to implement features that are not currently required. Focus on delivering the core functionality outlined in the initial specification.
*   **Refactor Only When Necessary:** Only refactor code when it addresses a significant problem or improves the overall design.

**5. Development & Productivity**

*   **Focus on Core Functionality:** All code must directly contribute to the primary goal of the AGENTS.md repository.
*   **Test-Driven Development:** All new code must be accompanied by comprehensive unit and integration tests. Prioritize test-driven development.
*   **Code Review:**  All code submitted for review should be meticulously scrutinized for adherence to these guidelines.
*   **Regular Refactoring:**  Periodic refactoring (small, incremental improvements) is encouraged to maintain code quality.
*   **Traceability:** Each module and function should have a clear and concise description of its purpose.

**6. Code Length Constraint:**

*   Maximum code length: 180 lines.
*   Strictly adhere to the line length limit.

**7. Test Coverage Requirements:**

*   Minimum test coverage: 80%.
*   All code must be covered by at least 80% of tests.  Test coverage should be automated wherever possible.

**8. File Structure & Organization:**

*   **Naming Conventions:** Use consistent naming conventions (e.g., camelCase, snake_case).
*   **Comments:**  Use clear and concise comments to explain complex logic, assumptions, and potential limitations.
*   **Documentation:**  Provide detailed documentation within each module, explaining its purpose, inputs, and outputs.

**9.  Coding Style:**

*   Use consistent indentation and spacing.
*   Follow a specified coding style guide (if one exists).
*   Adhere to standard Python/Language-specific conventions.

**10.  Maintainability**

*   Code should be easily understandable and modified by other developers.
*   Use clear and concise variable names.
*   Avoid overly complex logic.

**11.  External Dependencies:**

*   All external dependencies should be clearly documented and managed (e.g., via a `requirements.txt` or similar file).
*   Dependencies should be versioned appropriately.

**12.  Error Handling:**

*   Implement robust error handling and logging.
*   Provide informative error messages.

**13.  Data Structures & Algorithms:**

*   Employ appropriate data structures and algorithms for each task.
*   Consider performance implications when choosing data structures.

**14.  Error Prevention:**

*   Design the code to be resilient to common errors and unexpected inputs.
*   Use input validation to prevent invalid data from being processed.

These guidelines are a living document and should be reviewed and updated periodically as the project evolves.
```