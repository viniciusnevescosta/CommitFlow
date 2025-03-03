# CommitFlow :rocket:  
A Python script to simplify creating **semantic commits** with emojis, type validation, and interactive prompts.  
Automates `git add` and `git commit` in one step.  

---

## Features  
- Interactive commit type selection with emojis and descriptions  
- Title/description validation (length, required fields)  
- Previews commit messages before confirmation  
- Handles `git add` automatically for specified files 

---

## Quick Start  
Run directly from GitHub using `curl` (no installation needed):  

```bash
# Basic usage:  
curl -sSL https://raw.githubusercontent.com/viniciusnevescosta/CommitFlow/main/handlecommit.py | python3 - -- file1.txt file2.js
```

## How It Works

    - Stage Files: Provide files as arguments (e.g., file1.txt file2.js).
    - Select Commit Type: Choose from 20+ semantic types (e.g., feat, fix, docs).
    - Enter Details: Add a title (required) and description (optional).
    - Confirm: Preview and finalize the commit.
    
## Prerequisites

- Python 3.6+
- Git installed locally

## Notes

-  For security, verify the script source before running.
- Customize COMMIT_TYPES in the script to match your team’s conventions.