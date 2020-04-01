# SYSTEM_MANUFACTURING_INFORMATION

```C
typedef struct _SYSTEM_MANUFACTURING_INFORMATION { // x86 = 12, x64 = 24
   ULONG          Options;                                          // 0x000 0x000
   UNICODE_STRING ProfileName;                                      // 0x004 0x008
} SYSTEM_MANUFACTURING_INFORMATION, *PSYSTEM_MANUFACTURING_INFORMATION;
```
