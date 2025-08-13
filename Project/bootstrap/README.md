# 📂 Bootstrap Directory  
Contains **Laravel framework bootstrapping files**.  

### ✅ **What Goes Here?**  
- `app.php` → Initializes Laravel application  
- `cache/` → Compiled service container files  
- Autoload files  

### 🚫 **What Doesn’t Belong?**  
- Custom application logic (→ `/app/`)  
- Config files (→ `/config/`)  

### 🔧 **Contributor Guidelines**  
- Do **not modify** files here manually.  
- Clear cache with:  
  ```bash
  php artisan optimize:clear