# GatherFolderContext

**GatherFolderContext** is a simple script that collects a hierarchical map of the current folder (and its subfolders), including the text of each file. It then outputs everything into a single text file named after the top-level folder.

## 🚀 Setup

### 1️⃣ Clone the Repository
```
git clone <your-repo-url>
cd gatherfoldercontext
```

### 2️⃣ Make the Script Executable
```
chmod +x gatherfoldercontext
```

### 3️⃣ Move the Script to Your Path
```
cp gatherfoldercontext ~/.local/bin/  
```

### 4️⃣ Ensure the Folder is in Your Path
If it's not already in your path, add it:
```
export PATH="$PATH:$HOME/.local/bin"
```

### 5️⃣ Reload Your Shell Configuration
```
source ~/.bashrc
```
(Use `source ~/.zshrc` if you're using Zsh.)

---

## 🎯 Usage

Run the script in any folder you want to gather information on:
```
gatherfolderinfo -e "node_modules build"
```

This will generate a structured output file with the contents of the specified folders.

Happy coding! 🚀
