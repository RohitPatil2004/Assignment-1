# Assignment-1
---

## **1. Creating and Renaming Files/Directories**

### **Commands:**

```bash
mkdir test_dir                            # Create a directory named test_dir
cd test_dir                               # Move into the directory
touch example.txt                         # Create an empty file
mv example.txt renamed_example.txt        # Rename the file
```

### **Explanation:**

* `mkdir`: Makes a new directory.
* `touch`: Creates an empty file.
* `mv`: Moves or renames a file.

---

## **2. Viewing File Contents**

### **Commands:**

```bash
cat /etc/passwd               # View full contents
head -n 5 /etc/passwd         # First 5 lines
tail -n 5 /etc/passwd         # Last 5 lines
```

### **Explanation:**

* `cat`: Concatenates and displays file content.
* `head -n 5`: Shows first 5 lines.
* `tail -n 5`: Shows last 5 lines.

---

## **3. Searching for Patterns**

### **Command:**

```bash
grep "root" /etc/passwd
```

### **Explanation:**

* `grep`: Searches for matching text (case-sensitive by default).

---

## **4. Zipping and Unzipping**

### **Commands:**

```bash
cd ..
zip -r test_dir.zip test_dir                 # Compress the test_dir directory
unzip test_dir.zip -d unzipped_dir           # Unzip into a new directory
```

### **Explanation:**

* `zip -r`: Recursively compresses a folder.
* `unzip`: Extracts zipped files.

---

## **5. Downloading Files**

### **Command:**

```bash
wget https://example.com/sample.txt
```

### **Explanation:**

* `wget`: Command-line tool to download files from the web.

*Note: Replace with a valid URL if `example.com` doesn’t have the file.*

---

## **6. Changing Permissions**

### **Commands:**

```bash
touch secure.txt
chmod 444 secure.txt
```

### **Explanation:**

* `chmod 444`: Sets read-only permission for everyone.

---

## **7. Working with Environment Variables**

### **Command:**

```bash
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```

### **Explanation:**

* `export`: Creates a new environment variable.
* `echo $MY_VAR`: Displays the value.

---
