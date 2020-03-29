# PROCESS_STACK_ALLOCATION_INFORMATION_EX

```C
typedef struct _PROCESS_STACK_ALLOCATION_INFORMATION_EX { // x86 = 28, x64 = 40
   ULONG PreferredNode;                                                       // 0x000 0x000
   ULONG Reserved0;                                                           // 0x004 0x004
   ULONG Reserved1;                                                           // 0x008 0x008
   ULONG Reserved2;                                                           // 0x00c 0x00c
   PROCESS_STACK_ALLOCATION_INFORMATION AllocInfo;                            // 0x010 0x010
} PROCESS_STACK_ALLOCATION_INFORMATION_EX, *PPROCESS_STACK_ALLOCATION_INFORMATION_EX;
```
