# SYSTEM_LEGACY_DRIVER_INFORMATION

```C
typedef struct _SYSTEM_LEGACY_DRIVER_INFORMATION { // x86 = 12, x64 = 24
   ULONG          VetoType;                                         // 0x000 0x000
   UNICODE_STRING VetoList;                                         // 0x004 0x008
} SYSTEM_LEGACY_DRIVER_INFORMATION, *PSYSTEM_LEGACY_DRIVER_INFORMATION;
```
