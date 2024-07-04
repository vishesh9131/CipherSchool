# Lecture-6 GitLab

## Introduction to Version Control

### What is Version Control?
If we are editing or working on a saved document and making some changes and unfortunately the new updated version brings up some error, then without any hassle the document returns to its previous version. Version Control is the most sophisticated and hassle-free way of manipulating a document.

### Why is Version Control crucial for Software Development?
Version Control lets everyone work on their own versions independently, resulting in non-interference from any second person.

---

One of the most common version control systems is GIT. Its distributed nature and robust branching make it a favorite in the corporate world and among independent developers.

### What is Git?
Git is a distributed version control system. In this, every developer working on a project with Git has a complete copy of the project history on their local machines. This allows for managing changes in their respective versions.

#### Key Features:
- Snapshot
- Branches
- Local & Remote repositories

#### Basic Git Commands:
- `git init`
- `git add`
- `git commit`
- `git status`

---

### What is a Repository?
It is a storage space or a directory that belongs to a file in some project. These are of two types:

- **Local**: These repositories are stored on someone's own system or workspace where one can make or commit their own changes.
- **Remote**: These repositories are stored on the server directly.

---

### What are Branches?
Suppose a developer is working on a project, the complete process or life cycle to make a project is called a Master Branch. In this, each developer creates a separate branch for themselves which only involves their part of the role in the project, making it independent from someone else's work. This is called Branching. `Branch` and `Checkout` are the two commands used to create a branch and switch between the branches in Git.

### What is Push?
Git Push is a Git command used to push the code present in your local repository to the remote repository or the main branch where others can access it. Before doing the push command, we need to make sure that our changes are committed.
Steps: `Add` -> `Commit` -> `Push`

### What is Pull Request?
It is a request made to merge your code to the main branch where the developer can discuss, review, and