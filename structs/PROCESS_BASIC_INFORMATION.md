# PROCESS_BASIC_INFORMATION

```C
typedef struct _PROCESS_BASIC_INFORMATION { // x86 = 24, x64 = 48
   NTSTATUS  ExitStatus;                                     // 0x000 0x000
   PPEB      PebBaseAddress;                                 // 0x004 0x008
   ULONG_PTR AffinityMask;                                   // 0x008 0x010
   KPRIORITY BasePriority;                                   // 0x00c 0x018 (typedef LONG KPRIORITY;)
   ULONG_PTR UniqueProcessId;                                // 0x010 0x020
   ULONG_PTR InheritedFromUniqueProcessId;                   // 0x014 0x028
} PROCESS_BASIC_INFORMATION, *PPROCESS_BASIC_INFORMATION;
```
