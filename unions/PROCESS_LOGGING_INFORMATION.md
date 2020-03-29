# PROCESS_LOGGING_INFORMATION

```C
typedef union _PROCESS_LOGGING_INFORMATION { // same size in both x86 and x64
   ULONG    Flags;                                                         // 0x000 0x000
   struct {
      ULONG EnableReadVmLogging : 1;                                       // 0x000 0x000
      ULONG EnableWriteVmLogging : 1;                                      // 0x000 0x000
      ULONG EnableProcessSuspendResumeLogging : 1;                         // 0x000 0x000
      ULONG EnableThreadSuspendResumeLogging : 1;                          // 0x000 0x000
      ULONG Reserved : 28;                                                 // 0x000 0x000
   };
} PROCESS_LOGGING_INFORMATION, *PPROCESS_LOGGING_INFORMATION;
```
