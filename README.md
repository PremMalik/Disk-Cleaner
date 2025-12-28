

## PowerShell (Best on Windows)

### 🔥 Securely wipe a whole disk (ZERO fill)

> **ADMIN REQUIRED**
> ⚠️ DESTROYS ALL DATA — DOUBLE-CHECK DISK NUMBER

```powershell
diskpart
```

Then inside diskpart:

```
list disk
select disk 1
clean all
```

✅ `clean all` = writes **zeros to every sector**
❌ `clean` alone = NOT secure

This is **the most reliable Windows-native method**.

