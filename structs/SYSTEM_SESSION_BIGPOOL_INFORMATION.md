# SYSTEM_SESSION_BIGPOOL_INFORMATION

```C
typedef struct _SYSTEM_SESSION_BIGPOOL_INFORMATION { // x86 = 24, x64 = 40
   ULONG_PTR            NextEntryOffset;                              // 0x000 0x000
   ULONG                SessionId;                                    // 0x004 0x008
   ULONG                Count;                                        // 0x008 0x00c
   SYSTEM_BIGPOOL_ENTRY AllocatedInfo[1];                             // 0x00c 0x010
} SYSTEM_SESSION_BIGPOOL_INFORMATION, *PSYSTEM_SESSION_BIGPOOL_INFORMATION;
```
