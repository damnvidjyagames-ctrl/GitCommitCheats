Here’s a clean, professional, repo‑ready **README.md** that presents your mental model and both flag lists in a polished, operator‑grade format. It’s structured so you can drop it directly into any GitHub project.

---

# ⚡ Command‑Line & Git Quick Reference

A compact, beginner‑friendly cheat sheet designed to build strong mental models for Linux navigation and Git workflows. Perfect for Termux, pentesting labs, and daily operator practice.

---

## ⚡ Quick Mental Model

| Command | Meaning |
|--------|---------|
| `ls -a` | Show everything, including hidden files |
| `git commit -m "msg"` | Save your changes with a message |

You’re essentially telling the system:

- **ls:** “Show me all files.”  
- **git:** “Save this change and label it with this message.”

These two ideas form the foundation of understanding how Linux reveals information and how Git records your work.

---

## 🔧 Top Termux / Linux Flags (10)

1. **`ls -a`**  
   Show all files, including hidden dotfiles.

2. **`ls -l`**  
   Long format: permissions, owners, timestamps, sizes.

3. **`ls -la`**  
   Combine both: long format + hidden files.

4. **`cp -r`**  
   Copy directories recursively.

5. **`mv -i`**  
   Move files but ask before overwriting.

6. **`rm -i`**  
   Delete files with a confirmation prompt.

7. **`rm -r`**  
   Remove directories recursively.

8. **`rm -rf`**  
   Force delete recursively.  
   *(Operator note: use only when you’re absolutely sure.)*

9. **`find . -type f`**  
   Find all files under the current directory.

10. **`grep -i`**  
    Case‑insensitive search inside files.

---

## 🧰 Top Git Flags (10)

11. **`git add .`**  
    Stage everything, including hidden files.

12. **`git status -s`**  
    Short, clean status output.

13. **`git commit -m "msg"`**  
    Commit with a message (avoids opening an editor).

14. **`git log --oneline`**  
    Compact commit history.

15. **`git diff --staged`**  
    Show changes that are staged but not committed.

16. **`git push -u origin main`**  
    Push and set upstream so future pushes are simple.

17. **`git pull --rebase`**  
    Pull updates without messy merge commits.

18. **`git clone --depth 1 URL`**  
    Shallow clone — fast, minimal history.

19. **`git rm -r`**  
    Remove tracked files or folders.

20. **`git restore --staged FILE`**  
    Unstage something you added by mistake.

---

If you want, I can format this with emojis, badges, sections, or a more “hacker‑lab” aesthetic to match your pentesting repo style.
