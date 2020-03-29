# PROCESS_STACK_ALLOCATION_INFORMATION

```C
typedef struct _PROCESS_STACK_ALLOCATION_INFORMATION { // x86 = 12, x64 = 24
   SIZE_T ReserveSize;                                                 // 0x000 0x000
   SIZE_T ZeroBits;                                                    // 0x004 0x008
   PVOID StackBase;                                                    // 0x008 0x010
} PROCESS_STACK_ALLOCATION_INFORMATION, *PPROCESS_STACK_ALLOCATION_INFORMATION;
```
