# PROCESS_WORKING_SET_CONTROL

```C
typedef struct _PROCESS_WORKING_SET_CONTROL { // same size in both x86 and x64
   ULONG Version;                                                             // 0x000 0x000
   PROCESS_WORKING_SET_OPERATION Operation;                                   // 0x004 0x004
   ULONG Flags;                                                               // 0x008 0x008
} PROCESS_WORKING_SET_CONTROL, *PPROCESS_WORKING_SET_CONTROL;
```
