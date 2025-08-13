
---

### **📁 `/lang/` – Localization Files**  
```markdown
# 📂 Lang Directory  
**Multi-language translation files**.  

### ✅ **What Goes Here?**  
- JSON or PHP translation files (e.g., `en.json`, `es/validation.php`)  
- Vendor overrides (`vendor/{package}/`)  

### 🚫 **What Doesn’t Belong?**  
- Hardcoded strings in views/controllers  
- Config translations (→ `/config/`)  

### 🔧 **Contributor Guidelines**  
- Use **translation keys** in Blade:  
  ```php
  {{ __('messages.welcome') }}