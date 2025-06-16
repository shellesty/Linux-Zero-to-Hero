This section explains basic Linux commands used to work with files and folders.
🔹 ls

Shows files and folders in the current folder.

    ls -ltr: Shows details like size, date, and permissions.

🔹 cd

Changes to a different folder.

    cd / → Go to the root folder.

    cd .. → Go back one folder.

    cd ~ or cd → Go to your home folder.

🔹 mkdir

Makes a new folder.

    mkdir myfolder → Create one folder.

    mkdir -p folder1/folder2 → Create nested folders.

🔹 rmdir

Deletes an empty folder.

    rmdir myfolder

🔹 rm

Deletes files or folders.

    rm file.txt → Delete a file.

    rm -f file.txt → Force delete a file.

    rm -rf myfolder → Delete a folder and all its contents.

🔹 touch

Creates a new empty file.

    touch notes.txt

🔹 cp

Copies a file.

    cp file1.txt file2.txt → Makes a copy of file1.txt and names it file2.txt.

🔹 mv

Moves or renames files/folders.

    mv oldname.txt newname.txt → Rename the file.

    mv file.txt /home/user/ → Move the file to another folder.

🔹 vim or vi

Opens a file in a text editor (in the terminal).

    vim file.txt

Use i to insert text, Esc to exit insert mode, :wq to save and quit.
🔹 cat

Shows the full content of a file.

    cat file.txt

🔹 less

Views large files page by page.

    less bigfile.log (Press q to quit)

🔹 head

Shows the first lines of a file.

    head -5 file.txt → Shows the first 5 lines

🔹 tail

Shows the last lines of a file.

    tail -5 file.txt → Shows the last 5 lines

🔹 tac

Shows the file in reverse order (last line first).

    tac file.txt

🔹 echo

Prints a message or saves text to a file.

    echo "Hello" → Shows "Hello"

    echo "Hi" > file.txt → Writes “Hi” to the file (replaces content)

    echo "Bye" >> file.txt → Adds “Bye” to the end of the file
