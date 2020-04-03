# SYSTEM_SESSION_POOLTAG_INFORMATION

```C
typedef struct _SYSTEM_SESSION_POOLTAG_INFORMATION { // x86 = 40, x64 = 56
   ULONG_PTR      NextEntryOffset;                                    // 0x000 0x000
   ULONG          SessionId;                                          // 0x004 0x008
   ULONG          Count;                                              // 0x008 0x00c
   SYSTEM_POOLTAG TagInfo[1];                                         // 0x00c 0x010
} SYSTEM_SESSION_POOLTAG_INFORMATION, *PSYSTEM_SESSION_POOLTAG_INFORMATION;
```
