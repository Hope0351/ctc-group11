# 📂 Config Directory  
Contains **app-wide configuration** (API keys, services, packages).  

### ✅ **What Goes Here?**  
- `app.php` (Core settings)  
- `database.php` (DB connections)  
- `auth.php` (Authentication rules)  
- Custom configs (e.g., `mailchimp.php`)  

### 🚫 **What Doesn’t Belong?**  
- Environment variables (→ `.env`)  
- Business logic (→ `/app/`)  

### 🔧 **Contributor Guidelines**  
- Never commit **sensitive data** (use `.env` instead).  
- Document new configs in `config/README.md`.  