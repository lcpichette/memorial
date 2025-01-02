# Contributing to Memorial

I value you -- taking the time to read this, contributing to this project, and helping make a meaningful impact to those who've experienced immeasurable loss.

## Getting Started

1. **Fork the Repository**  
   Create a fork of this repository to make your changes.

2. **Clone the Repository**  
   Clone your forked repository to your local machine using:
   ```bash
   git clone https://github.com/[your-username]/memorial.git
   ```

3. **Install Dependencies**  
   Navigate to the project folder and install dependencies:
   ```bash
   cd memorial
   nvm use
   pnpm install
   ```

4. **Set Up Your Environment**  
   Follow the instructions in the `README.md` to set up your development environment.

5. **Sync with Main**
   - Before starting work, ensure your branch is up to date with the main branch:
     ```bash
     git checkout main
     git pull origin main
     ```

## How to Contribute

### Glossary

1. Remembered Souls - Cards which contain an image, name, cause of death, and brief description of a life lost.
2. Our Mission of Remembrance - The root page of the project which describes the project and its mission.
3. In Memoriam - The page showing the list of Remembered Souls
4. Profile Page - Standard profile page for those who have created their account (required to post lost loved ones)
5. Your Submissions Page - The page in which registered users can view their postings of lost loved ones.
6. A Life Remembered - The page in which stories and greater details of a lost loved one can be shared.

### Reporting Issues

- Check the [existing issues](https://github.com/lcpichette/healthcare-memorial/issues) to ensure your issue hasn’t already been reported.
- If new, create a detailed issue, providing all necessary context, screenshots, or error messages.

### Working on Issues

1. **Find an Issue**
   - Browse the [issues list](https://github.com/[org-name]/[project-name]/issues) for an issue to work on.
   - Look for issues labeled `good first issue` if you’re a beginner.

2. **Assign Yourself**
   - Assign yourself to the issue so others know it’s being worked on.

3. **Label as In-Progress**
   - Add the `in-progress` label to indicate that work has started on the issue.

4. **Work on Your Feature or Bugfix**
   - Create a new branch for your changes:
     ```bash
     git checkout -b feature/issue-title
     ```
   - Commit your changes with meaningful messages:
     ```bash
     git commit -m "Fix: [short description of fix]"
     ```

5. **Testing Your Changes**
   - Ensure your code is thoroughly tested.
   - Run existing tests and add new ones as required.

6. **Pull in Latest Changes**
   - Regularly pull in changes from the main branch to avoid merge conflicts:
     ```bash
     git pull origin main
     ```

7. **Submit a Pull Request**
   - Push your changes to your fork:
     ```bash
     git push origin feature/issue-title
     ```
   - Open a pull request (PR) to the main repository.
   - Link your PR to the issue it addresses.

### Reviewing Pull Requests

- Reviewers should:
  - Check the code for clarity, functionality, and adherence to coding standards.
  - Test the changes if applicable.
  - Provide constructive feedback and request changes if needed.

- Contributors should:
  - Address all feedback promptly.
  - Ensure the PR passes all CI checks before re-submitting for review.

### Dropping an Issue

- If you decide to stop working on an issue:
  1. Unassign yourself from the issue.
  2. Remove the `in-progress` label.

### QA Review

- Once your pull request is ready:
  1. Change the label from `in-progress` to `QA`.
  2. Wait for maintainers or other contributors to review your PR.

---

## Code of Conduct

Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful and considerate in all interactions.

---

