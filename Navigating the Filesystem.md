# Navigating the Filesystem

## pwd

```bash
# Show current working directory
pwd
```

Output:

```text
Desktop/devops-practice/linux-cli-practice
```

---

## ls

```bash
# List files and directories
ls
```

Output:

```text
'Archive & Compression.md'   Logs.md                        'Process Management.md'  'Text Processing.md'
```

---

## ls -l

```bash
# List files with details
ls -l
```

Output:

```text
-rwxrwxrwx 1 kartik kartik   0 Jul 19 12:58 'Archive & Compression.md'
-rwxrwxrwx 1 kartik kartik   0 Jul 19 12:58 'File Operations.md'
-rwxrwxrwx 1 kartik kartik   0 Jul 19 12:58 'File Permissions.md'
-rwxrwxrwx 1 kartik kartik   0 Jul 19 12:58  Logs.md
```

---

## ls -a

```bash
# Show hidden files
ls -a
```

Output:

```text

```
 .     'Archive & Compression.md'   Logs.md                        'Process Management.md'  'Text Processing.md'
 ..    'File Operations.md'        'Navigating the Filesystem.md'   README.md               'User Management.md'
 .git
---

## cd

```bash
# Change to another directory
cd devops-practice/
```

Output:

```text

```
kartik@LAPTOP-NPJFOSTG:/mnt/c/Users/karti/Desktop$ cd devops-practice/
kartik@LAPTOP-NPJFOSTG:/mnt/c/Users/karti/Desktop/devops-practice$ 
---

## mkdir

```bash
# Create a new directory
mkdir folder1
```

Output:

```text

```
ls
folder1  linux-cli-practice
---

## rmdir

```bash
# Remove an empty directory
rmdir demo
```

Output:

```text
ls
linux-cli-practice
```

---

## tree

```bash
# Display directory structure
tree
```

Output:

```text

```
tree
.
├── Archive & Compression.md
├── File Operations.md
├── File Permissions.md
├── Logs.md
├── Navigating the Filesystem.md
├── Networking.md
├── Process Management.md
├── README.md
├── Searching.md
├── Text Processing.md
├── User Management.md
└── Viewing Files.md

1 directory, 12 files
---

## find

```bash
# Find a file
find . -name "*.md"
```

Output:

```text
find . -name "*.md"
./Archive & Compression.md
./File Operations.md
./File Permissions.md
./Logs.md
./Navigating the Filesystem.md
./Networking.md
```