# Contributing to Open Source Portfolio Template

First off, thank you for considering contributing!

## Ways to Contribute

### Reporting Bugs
- Use the  [GitHub Issues tab](https://github.com/kayspace/portfolio-template/issues)
- Check if the bug has already been reported
- Include detailed steps to reproduce
- Add screenshots if helpful

### Suggesting Features
- Open a GitHub Issue with the "enhancement" label
- Describe the feature clearly
- Explain why it would be useful
- Consider how it fits with the project's goals

### Code Contributions

#### Before You Start
1. Check existing issues to see if someone's already working on it
2. For major changes, open an issue first to discuss
3. Fork the repository and create a new branch

#### Development Workflow
1. **Fork** the repo on GitHub
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/kayspace/portfolio-template.git
   ```
3. **Check the issue**
   - Look at GitHub Issues and decide what you want to work on
   - Link your branch to the relevant issue if applicable

4. **Create a new branch for every change**
   ```bash
   git checkout master
   git pull origin master
   git checkout -b feature/short-description
   ```

   **Examples for branch names:**
   - `feature/dark-mode-toggle`
   - `fix/typo-navbar`
   - `bug/logic`
   - `update/documentation`
   - `refactor/code-logic`
   - `experiment/description`
   
   > Even small fixes should get their own branch — keeps the repo clean and PRs focused.

5. **Make changes locally**
   - Edit code, styles, etc.
   - Test thoroughly to make sure nothing else breaks

6. **Commit your changes**
   ```bash
   git add .
   git commit -m "fix: short-description (#1)"
   ```
   
   - Use clear, concise commit messages
   > Link to issue if relevant or if you are working on an issue: `(#issue_number)`

   **Examples for commit messages:**
   - `feat: short-description (issue_number)`
   - `fix: short-description (issue_number) `
   - `bug: short-description (issue_number)`
   - `update: short-description (issue_number)`
   - `refactor: short-description (issue_number)`

7. **Push branch to GitHub**
   ```bash
   git push origin feature/short-description
   ```

8. **Open a Pull Request**
   - Go to GitHub → your repo → Compare & pull request
   - Fill in:
     - **Title:** short, descriptive
     - **Description:** what changed, why, how tested
     - **Link issue:** `Fixes #<issue_number>`

9. **Review & merge**
   - Will review the code or have someone else reviewed
   - GitHub automatically closes linked issues if `Fixes #<issue_number>` is used

10. **Delete branch after merge**
    
    **Locally:**
    ```bash
    git checkout master
    git branch -d feature/short-description
    ```
    
    **Remotely:**
    ```bash
    git push origin --delete feature/short-description
    ```

11. **Update master before next change**
    ```bash
    git checkout master
    git pull origin master
    ```
    
    > Always start new changes from latest master.


#### Code Style Guidelines
- Use consistent indentation (2 or 4 spaces)
- Add comments for complex logic
- Use meaningful variable and function names
- Keep functions small and focused
- Test your changes across different browsers

#### Testing Your Changes
- Test on multiple browsers (Chrome, Firefox, Safari, Edge)
- Check mobile responsiveness
- Make sure all existing functionality still works

### Documentation
- Improve README or other docs
- Add code comments
- Fix typos and grammar

## Pull Request Guidelines

### Before Submitting
- [ ] Test your changes thoroughly
- [ ] Check that your code follows the project style
- [ ] Update documentation if needed
- [ ] Make sure all existing functionality still works

### Pull Request Template
When creating a PR, please include:

**What does this PR do?**
- Brief description of changes

**Why is this needed?**
- Explain the problem being solved

**How was this tested?**
- Describe testing steps
- Include screenshots if UI changes

**Checklist:**
- [ ] Code follows project style guidelines
- [ ] Changes have been tested
- [ ] Documentation updated (if needed)
- [ ] No breaking changes (or clearly documented)

## Getting Help

- Open an issue for questions 
- Check existing issues and PRs first
- Be patient - this is a volunteer project!

## Code of Conduct

### Be Respectful
- Be welcoming to newcomers
- Use inclusive language
- Respect different viewpoints
- Focus on constructive feedback

### Be Collaborative
- Help others learn and grow
- Share knowledge generously
- Give credit where it's due
- Ask questions when unclear

## Questions?

Don't hesitate to ask! Open an issue with the "question" label, and we'll help you get started.

---

Thank you for contributing to open source portfolio template! 