# PROCESS_MEMORY_EXHAUSTION_INFO

```C
typedef struct _PROCESS_MEMORY_EXHAUSTION_INFO { // x86 = 12, x64 = 16
   USHORT                         Version;                        // 0x000 0x000
   USHORT                         Reserved;                       // 0x002 0x002
   PROCESS_MEMORY_EXHAUSTION_TYPE Type;                           // 0x004 0x004
   ULONG_PTR                      Value;                          // 0x008 0x008
} PROCESS_MEMORY_EXHAUSTION_INFO, *PPROCESS_MEMORY_EXHAUSTION_INFO;
```
