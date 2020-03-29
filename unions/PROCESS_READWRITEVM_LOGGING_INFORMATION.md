# PROCESS_READWRITEVM_LOGGING_INFORMATION

```C
typedef union _PROCESS_READWRITEVM_LOGGING_INFORMATION { // same size in both x86 and x64
   UCHAR    Flags;                                                            // 0x000 0x000
   struct {
      UCHAR EnableReadVmLogging : 1;                                          // 0x000 0x000
      UCHAR EnableWriteVmLogging : 1;                                         // 0x000 0x000
      UCHAR Unused : 6;                                                       // 0x000 0x000
   };
} PROCESS_READWRITEVM_LOGGING_INFORMATION, *PPROCESS_READWRITEVM_LOGGING_INFORMATION;
```
