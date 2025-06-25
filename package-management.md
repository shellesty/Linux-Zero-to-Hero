# Package Management

Learn how to install, update, and remove software using `apt` (used in Ubuntu/Debian).

---

🔹 sudo apt update

Updates the list of available packages from the internet.

---

🔹 sudo apt upgrade

Upgrades all installed packages to their latest versions.

---

🔹 sudo apt install [package-name]

Installs a new package.

    Example: sudo apt install git

---

🔹 apt search [package-name]

Searches for a package in the list of available packages.

---

🔹 apt list --installed

Lists all packages currently installed on the system.

---

🔹 sudo apt remove [package-name]

Removes a package (but keeps its settings).

    Example: sudo apt remove nano

---

🔹 sudo apt purge [package-name]

Removes a package completely, including its config files.

---

🔹 sudo apt autoremove

Removes unused packages (dependencies no longer needed).

---

🔹 sudo apt clean

Cleans up downloaded `.deb` files to save disk space.

---

Tip: Always run `sudo apt update` before installing new software to make sure your system is up to date.
