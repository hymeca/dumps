# PROCESS_MEMORY_ALLOCATION_MODE

```C
typedef union _PROCESS_MEMORY_ALLOCATION_MODE { // same size in both x86 and x64
   ULONG    Flags;                                                           // 0x000 0x000
   struct {
      ULONG TopDown : 1;                                                     // 0x000 0x000
      ULONG Reserved : 1;                                                    // 0x000 0x000
   };
} PROCESS_MEMORY_ALLOCATION_MODE, *PPROCESS_MEMORY_ALLOCATION_MODE;
```
