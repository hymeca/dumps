# RTL_DEBUG_INFORMATION

```C
typedef struct _RTL_DEBUG_INFORMATION { // x86 = 104, x64 = 208
   HANDLE                                SectionHandleClient;                       // 0x000 0x000
   PVOID                                 ViewBaseClient;                            // 0x004 0x008
   PVOID                                 ViewBaseTarget;                            // 0x008 0x010
   ULONG_PTR                             ViewBaseDelta;                             // 0x00c 0x018
   HANDLE                                EventPairClient;                           // 0x010 0x020
   HANDLE                                EventPairTarget;                           // 0x014 0x028
   HANDLE                                TargetProcessId;                           // 0x018 0x030
   HANDLE                                TargetThreadHandle;                        // 0x01c 0x038
   ULONG                                 Flags;                                     // 0x020 0x040
   SIZE_T                                OffsetFree;                                // 0x024 0x048
   SIZE_T                                CommitSize;                                // 0x028 0x050
   SIZE_T                                ViewSize;                                  // 0x02c 0x058
   union {
      PRTL_PROCESS_MODULES               Modules;                                   // 0x030 0x060
      PRTL_PROCESS_MODULE_INFORMATION_EX ModulesEx;                                 // 0x030 0x060
   };
   PRTL_PROCESS_BACKTRACES               BackTraces;                                // 0x034 0x068
   PRTL_PROCESS_HEAPS                    Heaps;                                     // 0x038 0x070
   PRTL_PROCESS_LOCKS                    Locks;                                     // 0x03c 0x078
   PVOID                                 SpecificHeap;                              // 0x040 0x080
   HANDLE                                TargetProcessHandle;                       // 0x044 0x088
   PRTL_PROCESS_VERIFIER_OPTIONS         VerifierOptions;                           // 0x048 0x090
   PVOID                                 ProcessHeap;                               // 0x04c 0x098
   HANDLE                                CriticalSectionHandle;                     // 0x050 0x0a0
   HANDLE                                CriticalSectionOwnerThread;                // 0x054 0x0a8
   PVOID                                 Reserved[4];                               // 0x058 0x0b0
} RTL_DEBUG_INFORMATION, *PRTL_DEBUG_INFORMATION;
```
