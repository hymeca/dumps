# SYSTEM_POOLTAG_INFORMATION

```C
typedef struct _SYSTEM_POOLTAG_INFORMATION { // x86 = 32, x64 = 48
   ULONG          Count;                                      // 0x000 0x000
   SYSTEM_POOLTAG TagInfo[1];                                 // 0x004 0x008
} SYSTEM_POOLTAG_INFORMATION, *PSYSTEM_POOLTAG_INFORMATION;
```
