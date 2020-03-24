# PROCESS_BASIC_INFORMATION64

```C
typedef struct _PROCESS_BASIC_INFORMATION64 { // same size in both x86 and x64
   NTSTATUS  ExitStatus;                                     // 0x000 0x000
   ULONG     Pad1;                                           // 0x004 0x004
   ULONGLONG PebBaseAddress;                                 // 0x008 0x008
   ULONGLONG AffinityMask;                                   // 0x010 0x010
   KPRIORITY BasePriority;                                   // 0x018 0x018 (typedef LONG KPRIORITY;)
   ULONG     Pad2;                                           // 0x01c 0x01c
   ULONGLONG UniqueProcessId;                                // 0x020 0x020
   ULONGLONG InheritedFromUniqueProcessId;                   // 0x028 0x028
} PROCESS_BASIC_INFORMATION64, *PPROCESS_BASIC_INFORMATION64;
```
