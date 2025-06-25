# User and Group Management

Basic commands to create, manage, and delete users and groups in Linux.

---

🔹 useradd [username]

Adds a new user (without asking for details).

---

🔹 adduser [username]

Adds a new user and asks for password and user info.

---

🔹 passwd [username]

Sets or changes the password for a user.

---

🔹 userdel [username]

Deletes a user from the system.

---

🔹 groupadd [groupname]

Creates a new group.

---

🔹 usermod -aG [groupname] [username]

Adds a user to a group.

    Example: usermod -aG sudo john

---

🔹 id [username]

Shows the user's UID, GID, and group info.

---

🔹 whoami

Displays the current logged-in username.

---

🔹 su - [username]

Switches to another user account.

---

🔹 chmod [permissions] [file or directory]

Changes file or folder permissions.

    Example: chmod 755 script.sh

---

🔹 chown [owner]:[group] [file or directory]

Changes the owner and group of a file or folder.

    Example: chown shellesty:devops script.sh
