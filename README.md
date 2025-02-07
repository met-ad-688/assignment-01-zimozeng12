# Assignment 01 - StackOverflow Data Processing

### **💻 Author**
Name: Zimo Zeng

## 📌 Description
This project processes StackOverflow post data to:
- Collect system environment information
- Count the number of lines containing **"Python"** in CSV files using **Bash**
- Count the number of lines containing **"GitHub"** in CSV files using **Python**

## 📂 Folder Structure
```lua
root/  
├── _output/  
│   ├── os.txt  
│   ├── cpu.txt  
│   ├── mem.txt  
│   ├── pip3.txt  
│   ├── jupyter.txt  
│   ├── count_python.sh  
│   └── count_github.py  
├── README.md  

```

## 🛠 How to Run the Scripts

### **🔹1️⃣ Running `count_python.sh` (Shell)**
```bash
cd _output
chmod +x count_python.sh
./count_python.sh
```
- This script will output the total number of lines containing "Python" in the CSV dataset.

- Output Example:
After running the script, my output is:
```lua
Total lines containing 'python': 1064820
```
- This indicates that there are 1,064,820 lines in the dataset that mention "Python".

### **🔹2️⃣ Running count_github.py (Python)**
```bash
cd _output
python3 count_github.py
```
- This script will output the total number of lines containing "GitHub" in the CSV dataset.

- Output Example:
After running the script, my output is:
```lua
Total lines containing 'Github':32725
```
- This means there are 32,725 lines in the dataset that mention "GitHub".
