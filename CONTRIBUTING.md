# Contributing to AIRA Master Trainers Question Bank

🎉 Thank you for considering contributing! This project is part of **Hacktoberfest**, and we welcome contributions to expand and improve our AI literacy Question Bank.  

We especially encourage contributions from educators, trainers, students, and AI enthusiasts.  

Repository: [https://github.com/computingsg/airasg](https://github.com/computingsg/airasg)

---

## 📌 How Can I Contribute?

You can contribute in the following ways:

1. **Add New Questions**
   - Suggest **Pre/Post questions** for an existing module (M01–M12).
   - Propose questions for a new topic/module not yet covered.
   - Include both multiple-choice and open-ended questions if possible.

2. **Improve Existing Content**
   - Fix typos, grammar, or formatting in Markdown files.
   - Suggest better phrasing of questions/answers.
   - Add explanations for correct answers where relevant.

3. **Documentation**
   - Enhance clarity in `README.md` and `CONTRIBUTING.md`.
   - Add instructions or examples for educators on how to use the question bank.

---

## ⚙️ Contribution Process

You can contribute using either **Git (command-line)** or the **GitHub web interface**.

---

### 🔹 Option 1: Using Git (command-line)

1. **Fork the repository**  
   Go to [https://github.com/computingsg/airasg](https://github.com/computingsg/airasg) and click **Fork**.

2. **Clone your fork locally**  
   ```bash
   git clone https://github.com/your-username/airasg.git
   cd airasg
   ```

3. **Create a new branch**  
   ```bash
   git checkout -b add-questions-m03
   ```
   (Replace `m03` with the module you’re editing.)

4. **Make your changes**  
   - Edit the corresponding Markdown file (`m01.md` … `m12.md`).
   - Keep the format consistent:  
     - Odd questions = **Pre**, even questions = **Post**.  
     - Mark correct answers with `✅`.

   Example:
   ```markdown
   **Pre: What is an example of AI in healthcare?**  
   - A. Washing machines  
   - B. MRI scan image analysis ✅  
   - C. Social media feeds  
   - D. Airplane autopilot  
   ```

5. **Commit your changes**  
   ```bash
   git add .
   git commit -m "Added 2 new Pre/Post questions for Module 3"
   ```

6. **Push to your fork**  
   ```bash
   git push origin add-questions-m03
   ```

7. **Submit a Pull Request (PR)**  
   - Go to your fork on GitHub.  
   - Click **Compare & pull request**.  
   - Ensure the base repo is `computingsg/airasg` and the base branch is `main`.  
   - Add a clear PR description and submit.

---

### 🔹 Option 2: Using GitHub Web Interface (No Git Needed)

If you don’t have Git installed, you can contribute directly from your browser:

1. Go to the repo: [https://github.com/computingsg/airasg](https://github.com/computingsg/airasg).  
2. Click the file you want to edit (e.g., `m05.md`).  
3. Click the ✏️ (pencil icon) in the top right.  
4. Make your changes in the web editor.  
5. Scroll down and add a short commit message (e.g., *“Added 2 new Pre/Post questions to Module 5”*).  
6. Select **Create a new branch for this commit** and give it a descriptive name (e.g., `add-questions-m05`).  
7. Click **Propose changes**.  
8. On the next screen, click **Create pull request**.  

That’s it! 🎉 Your PR will be reviewed by the maintainers.

---

## ✅ Pull Request Guidelines

- Each PR should focus on **one module or one improvement**.  
- Provide a **clear description** of what you added/changed.  
- Ensure your PR is respectful, original, and helpful.  
- PRs will be reviewed before merging.

---

## 🎃 Hacktoberfest Participation

This repository follows Hacktoberfest guidelines:
- All valid PRs will be marked with the **hacktoberfest-accepted** label.  
- Spammy or irrelevant PRs will be marked as **invalid**.  

More info: [Hacktoberfest Official Site](https://hacktoberfest.com/)

---

## 📖 Code of Conduct

Be respectful and inclusive. We follow the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/).  

---

💡 **Tip**: If you’re not sure where to start, check the **Issues** tab for tasks labeled `good first issue` or `help wanted`.  

---

Happy contributing, and thank you for helping build a stronger AI literacy community! 🚀
