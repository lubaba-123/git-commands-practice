
# Git Commands Practice Notes

A quick guide to commonly used Git commands with explanations and examples.

---

## 1. `git init`

**What it does:**  
Initializes a new Git repository in the current directory.

**Use case:**  
Use this command when starting a new project and you want to track it using Git.

**Example:**
```bash
mkdir my-project
cd my-project
git init
```

---

## 2. `git clone`

**What it does:**  
Creates a local copy of a remote repository.

**Use case:**  
Use when you want to contribute to an existing GitHub project.

**Example:**
```bash
git clone https://github.com/username/repo-name.git
```

---

## 3. `git status`

**What it does:**  
Shows the status of changes (staged, unstaged, untracked).

**Use case:**  
Use to check what files have been modified or staged.

**Example:**
```bash
git status
```

---

## 4. `git add`

**What it does:**  
Stages changes to be committed.

**Use case:**  
Use before `git commit` to include changes.

**Example:**
```bash
git add file.txt
# or to stage all changes:
git add .
```

---

## 5. `git commit`

**What it does:**  
Records a snapshot of the staged changes.

**Use case:**  
Use to save your progress with a message.

**Example:**
```bash
git commit -m "Add feature X"
```

---

## 6. `git push`

**What it does:**  
Uploads local commits to the remote repository.

**Use case:**  
Use to share your commits with others or back them up.

**Example:**
```bash
git push origin main
```

---

## 7. `git pull`

**What it does:**  
Fetches and integrates changes from the remote repository.

**Use case:**  
Use to update your local branch with remote changes.

**Example:**
```bash
git pull origin main
```

---

## 8. `git branch`

**What it does:**  
Lists, creates, or deletes branches.

**Use case:**  
Use to create a new branch for a feature or to check existing ones.

**Example:**
```bash
git branch
git branch new-feature
```

---

## 9. `git checkout`

**What it does:**  
Switches branches or restores working tree files.

**Use case:**  
Use to move to a different branch.

**Example:**
```bash
git checkout new-feature
```

---

## 10. `git merge`

**What it does:**  
Merges another branch into the current branch.

**Use case:**  
Use to combine changes from a feature branch into `main`.

**Example:**
```bash
git checkout main
git merge new-feature
```

---
