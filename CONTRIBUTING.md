# Contributing to Moe Kyaw Aung Portfolio

First off, thank you for considering contributing to this project! 🎉

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Style Guidelines](#style-guidelines)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)

## 📜 Code of Conduct

This project adheres to a Code of Conduct. By participating, you are expected to uphold this code.

### Our Standards

- Be respectful and inclusive
- Accept constructive criticism gracefully
- Focus on what's best for the community
- Show empathy towards other contributors

## 🤝 How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues. When creating a bug report, include:

- **Clear title and description**
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Screenshots** (if applicable)
- **Browser and OS information**

**Example:**
```markdown
**Bug**: Navigation menu doesn't close on mobile

**Steps to Reproduce:**
1. Open site on mobile (iOS Safari)
2. Click hamburger menu
3. Click a nav link
4. Menu stays open

**Expected:** Menu should close
**Actual:** Menu remains open

**Browser:** Safari iOS 15.6

## 💻 Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/portfolio.git
cd portfolio

# Create feature branch
git checkout -b feature/your-feature-name

# Make changes
# Test in browser

# Commit changes
git add .
git commit -m "feat: add amazing feature"

# Push to your fork
git push origin feature/your-feature-name
```

### Testing Checklist

- [ ] Test on Chrome, Firefox, Safari
- [ ] Test on mobile devices
- [ ] Test dark/light mode
- [ ] Test all interactive features
- [ ] Validate HTML (https://validator.w3.org/)
- [ ] Check accessibility
- [ ] Test page load performance

## 🎨 Style Guidelines

### HTML

```html
<!-- ✅ Good -->
<section class="section" id="about">
  <div class="container">
    <h2 class="section-title">About Me</h2>
  </div>
</section>

<!-- ❌ Bad -->
<div id="about"><h2>About Me</h2></div>
```

### CSS

```css
/* ✅ Good - Use custom properties */
.button {
  background: var(--accent-cyan);
  padding: var(--spacing-md);
}

/* ❌ Bad - Hardcoded values */
.button {
  background: #00f0ff;
  padding: 15px;
}
```

### JavaScript

```javascript
// ✅ Good - ES6+, clear naming
const handleMenuToggle = () => {
  navMenu.classList.toggle('active');
};

// ❌ Bad - ES5, unclear naming
function f() {
  document.getElementById('x').classList.toggle('y');
}
```

### Naming Conventions

- **CSS Classes**: kebab-case (`.nav-menu`, `.section-title`)
- **JavaScript**: camelCase (`handleSubmit`, `isActive`)
- **IDs**: camelCase (`#navMenu`, `#contactForm`)
- **Custom Properties**: kebab-case (`--accent-cyan`, `--font-mono`)

## 📝 Commit Guidelines

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): subject

body (optional)

footer (optional)
```

### Types

- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation
- `style`: Code style (formatting, no logic change)
- `refactor`: Code refactoring
- `perf`: Performance improvement
- `test`: Adding tests
- `chore`: Maintenance tasks

### Examples

```bash
feat(navigation): add mobile hamburger menu
fix(contact): validate email format
docs(readme): update installation instructions
style(css): improve button hover effects
refactor(js): simplify filter function
perf(images): add lazy loading
```

## 🔄 Pull Request Process

1. **Update documentation** if needed
2. **Add tests** if applicable
3. **Ensure** all tests pass
4. **Update** README.md if needed
5. **Request review** from maintainers

### PR Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] Tested on Chrome
- [ ] Tested on Firefox  
- [ ] Tested on mobile
- [ ] Tested dark/light mode

## Screenshots
Add screenshots if applicable

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-reviewed code
- [ ] Commented complex code
- [ ] Updated documentation
- [ ] No new warnings
```

## 🐛 Issue Labels

- `bug`: Something isn't working
- `enhancement`: New feature request
- `documentation`: Documentation improvements
- `good first issue`: Good for newcomers
- `help wanted`: Extra attention needed
- `question`: Further information requested

## 🎯 Project Goals

- Maintain clean, readable code
- Keep page load time under 3 seconds
- Support latest 2 versions of major browsers
- Maintain Lighthouse score above 90
- Keep it accessible (WCAG 2.1 AA)

## 💬 Questions?

Feel free to:
- Open an issue for discussion
- Contact: moekyawaung@programmer.net
- Join our community discussions

---

**Thank you for contributing!** 🙏
```
