# SYSTEM_BIGPOOL_INFORMATION

```C
typedef struct _SYSTEM_BIGPOOL_INFORMATION { // x86 = 16, x64 = 32
   ULONG                Count;                                // 0x000 0x000
   SYSTEM_BIGPOOL_ENTRY AllocatedInfo[1];                     // 0x004 0x008
} SYSTEM_BIGPOOL_INFORMATION, *PSYSTEM_BIGPOOL_INFORMATION;
```
