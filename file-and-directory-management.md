# File and Directory Management

Basic commands to navigate, create, and manage files and directories in Linux.

🔹 ls

Shows files and folders in the current folder.

    ls -ltr: Shows details like size, date, and permissions.

🔹 cd

Changes the current directory.

    cd /       - Go to root
    cd ..      - Go one level up
    cd ~       - Go to home directory

🔹 mkdir [folder_name]

Creates a new directory.

    mkdir myfolder
    mkdir -p folder1/folder2  # creates nested folders

🔹 rmdir [folder_name]

Deletes an empty directory.

🔹 rm [file_name]

Deletes a file.

    rm -f file.txt      - Force delete
    rm -rf myfolder     - Delete folder and contents

🔹 touch [file_name]

Creates a new empty file.

🔹 cp [source] [destination]

Copies files or folders.

    cp file.txt backup.txt
    cp -r folder1 folder2  # copy folders recursively

🔹 mv [source] [destination]

Moves or renames files.

    mv oldname.txt newname.txt
    mv file.txt folder/

🔹 cat [file]

Shows the content of a file.

🔹 less [file]

Views file content page by page.

🔹 head -n 5 [file]

Shows the first 5 lines of a file.

🔹 tail -n 5 [file]

Shows the last 5 lines of a file.

🔹 echo "text"

Prints text or adds to a file.

    echo "Hello" > file.txt     # overwrite
    echo "World" >> file.txt    # append

🔹 vim [file] or vi [file]

Opens a file in a text editor.
