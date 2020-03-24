# PROCESS_FIBER_SHADOW_STACK_ALLOCATION_INFORMATION

```C
typedef struct _PROCESS_FIBER_SHADOW_STACK_ALLOCATION_INFORMATION { // x86 = 20, x64 = 32
   SIZE_T ReserveSize;                                    // 0x000 0x000
   SIZE_T CommitSize;                                     // 0x004 0x008
   ULONG  PreferredNode;                                  // 0x008 0x010
   ULONG  Reserved;                                       // 0x00c 0x014
   PVOID  Ssp;                                            // 0x010 0x018
} PROCESS_FIBER_SHADOW_STACK_ALLOCATION_INFORMATION,
*PPROCESS_FIBER_SHADOW_STACK_ALLOCATION_INFORMATION;
```
