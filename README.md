# Conventional Commits - Usage Guide

This repository follows the **Conventional Commits** standard for commit messages. This standard helps maintain an organized commit history, facilitates version automation, and creates a more efficient workflow. Below are the recommended commit types and how to use them correctly.

## Commit Types

### 1. **`feat`**: Adds a new feature
Use **`feat`** when adding a new functionality or feature to the code.

- Example:
  ```plaintext
  feat(auth): add login functionality
  ```

### 2. **`fix`**: Fixes a bug or error
Use **`fix`** to fix bugs or issues found in the code.

- Example:
  ```plaintext
  fix(login): fix validation bug
  ```

### 3. **`docs`**: Documentation changes
Use **`docs`** when you make changes to the documentation of the project.

- Example:
  ```plaintext
  docs(readme): update installation instructions
  ```

### 4. **`style`**: Code style changes (formatting, whitespace, etc.)
Use **`style`** when changing the style of the code without changing its behavior.

- Example:
  ```plaintext
  style(header): change font color
  ```

### 5. **`refactor`**: Code refactoring
Use **`refactor`** when rewriting a part of the code to improve its structure without changing its behavior or adding new features.

- Example:
  ```plaintext
  refactor(user): simplify user validation logic
  ```

### 6. **`test`**: Adds or modifies tests
Use **`test`** when adding new tests or modifying existing ones.

- Example:
  ```plaintext
  test(auth): add tests for login validation
  ```

### 7. **`chore`**: Changes to build tools or development processes
Use **`chore`** for changes that do not affect the actual code, such as updating dependencies or changing configuration files.

- Example:
  ```plaintext
  chore(deps): update react to 17.0.2
  ```

### 8. **`perf`**: Performance improvements
Use **`perf`** when optimizing a part of the code for performance.

- Example:
  ```plaintext
  perf(api): optimize data fetching
  ```

### 9. **`ci`**: Changes to continuous integration configuration
Use **`ci`** for modifications to continuous integration configuration files, like GitHub Actions or Travis CI.

- Example:
  ```plaintext
  ci: update build configuration
  ```

## Commit Structure

The commit structure follows this format:

```plaintext
<type>(<scope>): <message>
```

- **`<type>`**: Type of change (e.g., `feat`, `fix`, `docs`).
- **`<scope>`** (optional): Defines the scope or part of the code affected (e.g., `auth`, `login`).
- **`<message>`**: A clear description of what was done in the commit.

## Example Commits

- **New Feature:**
  ```plaintext
  feat(estoque): add list of products and quantities
  ```

- **Bug Fix:**
  ```plaintext
  fix(estoque): correct quantity display bug
  ```

- **Code Refactor:**
  ```plaintext
  refactor(estoque): simplify stock validation logic
  ```

- **Documentation Change:**
  ```plaintext
  docs(readme): update setup instructions for new users
  ```

## Benefits of Using Conventional Commits

- **Clarity**: Makes it easier to understand what was changed in the code via clear commit messages.
- **Version Automation**: Can be integrated with version release automation tools like **Semantic Release**.
- **Organized History**: Creates a cleaner and easier-to-follow commit history.
