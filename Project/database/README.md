# 📂 Database Directory  
Handles **database schema** and **test data**.  

### ✅ **What Goes Here?**  
- Migrations (`migrations/`)  
- Seeders (`seeders/`)  
- Factories (`factories/`)  

### 🚫 **What Doesn’t Belong?**  
- Raw SQL files (use migrations).  
- Business logic (→ `/app/Models/`).  

### 🔧 **Contributor Guidelines**  
- Name migrations like: `2024_01_01_create_users_table.php`.  
- Use **foreign key constraints** in migrations.  
- Seeders should **only** be used for testing/demo data.  