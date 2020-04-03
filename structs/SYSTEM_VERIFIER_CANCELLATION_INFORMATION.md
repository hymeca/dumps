# SYSTEM_VERIFIER_CANCELLATION_INFORMATION

```C
typedef struct _SYSTEM_VERIFIER_CANCELLATION_INFORMATION { // x86 = 2068, x64 = 4120
   ULONG                 CancelProbability;                                   // 0x000 0x000
   ULONG                 CancelThreshold;                                     // 0x004 0x004
   ULONG                 CompletionThreshold;                                 // 0x008 0x008
   ULONG                 CancellationVerifierDisabled;                        // 0x00c 0x00c
   ULONG                 AvailableIssues;                                     // 0x010 0x010
   SYSTEM_VERIFIER_ISSUE Issues[128];                                         // 0x014 0x018
} SYSTEM_VERIFIER_CANCELLATION_INFORMATION, *PSYSTEM_VERIFIER_CANCELLATION_INFORMATION;
```
