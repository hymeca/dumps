# SYSTEM_SECUREBOOT_INFORMATION

```C
typedef struct _SYSTEM_SECUREBOOT_INFORMATION { // same size in both x86 and x64
   BOOLEAN SecureBootEnabled;                                                // 0x000 0x000
   BOOLEAN SecureBootCapable;                                                // 0x001 0x001
} SYSTEM_SECUREBOOT_INFORMATION, *PSYSTEM_SECUREBOOT_INFORMATION;
```
