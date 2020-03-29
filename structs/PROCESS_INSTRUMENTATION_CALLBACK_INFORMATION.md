# PROCESS_INSTRUMENTATION_CALLBACK_INFORMATION

```C
typedef struct _PROCESS_INSTRUMENTATION_CALLBACK_INFORMATION { // x86 = 12, x64 = 16
   ULONG     Version;                                                         // 0x000 0x000
   ULONG     Reserved;                                                        // 0x004 0x004
   ULONG_PTR Callback;                                                        // 0x008 0x008
} PROCESS_INSTRUMENTATION_CALLBACK_INFORMATION,
*PPROCESS_INSTRUMENTATION_CALLBACK_INFORMATION;
```
