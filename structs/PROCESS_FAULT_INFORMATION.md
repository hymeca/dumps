# PROCESS_FAULT_INFORMATION

```C
typedef struct _PROCESS_FAULT_INFORMATION { // same size in both x86 and x64
   ULONG FaultFlags;                                     // 0x000 0x000
   ULONG AdditionalInfo;                                 // 0x004 0x004
} PROCESS_FAULT_INFORMATION, *PPROCESS_FAULT_INFORMATION;
```
