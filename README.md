# Script-of-pract1-to-4
  GNU nano 8.1                                                   script.sh
#!/bin/bash
echo "🐧 Q1. Directory Creation"


mkdir -p LabWork/A/Test
mkdir -p LabWork/B LabWork/C
echo "Directories created"


echo "🐧 Q2. File Operations"

touch LabWork/B/file1.txt LabWork/B/file2.txt LabWork/B/file3.txt
echo "3 files created in B"

cp LabWork/B/file1.txt LabWork/C/
echo "file1.txt copied to C"

mv LabWork/B/file2.txt LabWork/A/
echo "file2.txt moved to A"

rm LabWork/B/file3.txt
echo "file3.txt deleted"

echo ""
echo "=============================="
echo "🐧 Q3. Navigation Commands"
echo "=============================="

cd LabWork/A
echo "Moved to directory A"

echo "Current path:"
pwd

cd ..

**OUTPUT**
 Q1. Directory Creation
Directories created
 Q2. File Operations
3 files created in B
file1.txt copied to C
file2.txt moved to A
file3.txt deleted


 Q3. Navigation Commands

Moved to directory A
Current path:
/root/LabWork/A
Returned to parent directory


 Q4. Directory Structure

LabWork  [error opening dir]

0 directories, 0 files
tree command not installed


 Q5. File Creation and Writing

Content of data.txt:
Linux is powerful
Linux is secure
Linux is open-source


 Q6. Text Searching

Linux is powerful
Linux is secure
Linux is open-source


 Q7. Delete Files

Created multiple .txt files
All .txt files deleted


 Q8. User Input Script

Enter your name:
madhu
Welcome madhu
