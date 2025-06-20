# 🧪 Cowrie Honeypot Project – Kali Linux (UTM VM)

## 📸 Step-by-Step Screenshots

### ✅ Step 1: System Update
Checked for updates and ensured package compatibility before honeypot setup.  
![System Update](screenshots/01_system_update.png)

---

### ✅ Step 2: Installed Dependencies
Installed dependencies required to run Cowrie Honeypot.  
![Dependencies](screenshots/02_dependencies_installed.png)

---

### ✅ Step 3: Created Dedicated User
Created a dedicated user ‘nati’ to follow security best practices.  
![User Created](screenshots/03_created_user.png)

---

### ✅ Step 4: Switched to Cowrie User  
Switched to cowrie user for isolated honeypot setup.  
![Switched User](screenshots/04_switched_user.png)

---

### ✅ Step 5: Cloned Cowrie Files  
Downloaded Cowrie files into a working directory for setup.  
![Git Clone](screenshots/05_downloaded_files.png)

---

### ✅ Step 6: Virtual Environment  
Using virtual environment to keep Cowrie dependencies isolated.  
![Venv](screenshots/06_virtual_env.png)

---

### ✅ Step 7: Installed Python Requirements  
Installed Cowrie’s required Python packages inside the virtual environment.  
![Requirements Installed](screenshots/07_installed_requirements.png)

---

### ✅ Step 8: Edited Config File  
Changed Cowrie’s SSH port to 2222 to avoid conflict with real SSH.  
![Config](screenshots/08a_ssh_port_config.png)
![Screenshot 2](screenshots/08b_ssh_port_config.png)

---

### ✅ Step 9: Started Honeypot  
Started the honeypot so it can listen for fake SSH/Telnet logins.  
![Cowrie Running](screenshots/09a_started_honeypot.png)
![Cowrie Running](screenshots/09b_started_honeypot.png)
![Cowrie Running](screenshots/09c_started_honeypot.png)


---

### ✅ Step 10: Log Output  
Log files show unauthorized login attempts and interaction history.  
![Logs](screenshots/10_log_screenshot.png)
![Screenshot 2](screenshots/10b_log_screenshot.png)
