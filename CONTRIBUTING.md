# Contributing Guide 🎉

Welcome! This repository is designed to help beginners learn how to contribute to open source projects on GitHub. Follow these simple steps to make your first contribution!

## 📋 Prerequisites

- A GitHub account
- Git installed on your computer
- A text editor (VS Code, Sublime Text, Notepad++, etc.)

## 🚀 How to Contribute

### Step 1: Fork the Repository

1. Click the **Fork** button at the top right of this repository
2. This creates a copy of the repository in your GitHub account

### Step 2: Clone Your Fork

Open your terminal/command prompt and run:

```bash
git clone https://github.com/YOUR-USERNAME/session-repo1.git
cd session-repo1
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 3: Create a New Branch

```bash
git checkout -b add-your-name
```

Replace `your-name` with your actual name (e.g., `add-john-doe`).

### Step 4: Make Your Changes

1. Open `index.html` in your text editor
2. Find the comment that says `<!-- Add your contributor card below this line -->`
3. Copy the example contributor card div above it
4. Paste it below the comment
5. Update the information with your details:

```html
<div class="contributor-card">
    <h2 class="name">Your Name</h2>
    <p class="place">📍 Your City, Country</p>
    <p class="college">🎓 Your College/University</p>
</div>
```

### Step 5: Save and Test

1. Save the file
2. Open `index.html` in your web browser to see your changes
3. Make sure your card appears correctly

### Step 6: Commit Your Changes

```bash
git add index.html
git commit -m "Add [Your Name] to contributors"
```

### Step 7: Push to GitHub

```bash
git push origin add-your-name
```

### Step 8: Create a Pull Request

1. Go to your forked repository on GitHub
2. Click the **Compare & pull request** button
3. Add a title like "Add [Your Name] to contributors"
4. Add a description explaining your changes
5. Click **Create pull request**

## ✅ What to Expect

- A maintainer will review your pull request
- They may suggest some changes
- Once approved, your changes will be merged!
- Congratulations! You've made your first contribution! 🎊

## 💡 Tips

- Make sure your code follows the existing format
- Only change the contributor card section
- Don't modify the CSS unless you're improving it for everyone
- Be patient - reviews may take some time

## ❓ Need Help?

If you have any questions, feel free to:
- Open an issue
- Ask in the pull request comments
- Check out [GitHub's documentation](https://docs.github.com)

## 📚 Learning Resources

- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [GitHub Hello World](https://guides.github.com/activities/hello-world/)
- [Markdown Guide](https://www.markdownguide.org/)

Happy Contributing! 🚀
