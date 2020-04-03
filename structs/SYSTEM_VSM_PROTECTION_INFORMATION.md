# SYSTEM_VSM_PROTECTION_INFORMATION

```C
typedef struct _SYSTEM_VSM_PROTECTION_INFORMATION { // same size in both x86 and x64
   BOOLEAN DmaProtectionsAvailable;                                             // 0x000 0x000
   BOOLEAN DmaProtectionsInUse;                                                 // 0x001 0x001
   BOOLEAN HardwareMbecAvailable;                                               // 0x002 0x002
} SYSTEM_VSM_PROTECTION_INFORMATION, *PSYSTEM_VSM_PROTECTION_INFORMATION;
```
