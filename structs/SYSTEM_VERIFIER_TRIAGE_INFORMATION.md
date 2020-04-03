# SYSTEM_VERIFIER_TRIAGE_INFORMATION

```C
typedef struct _SYSTEM_VERIFIER_TRIAGE_INFORMATION { // x86 = 544, x64 = 568
   ULONG     ActionTaken;                                              // 0x000 0x000
   ULONG_PTR CrashData[5];                                             // 0x004 0x008
   ULONG     VerifierMode;                                             // 0x018 0x030
   ULONG     VerifierFlags;                                            // 0x01c 0x034
   WCHAR     VerifierTargets[256];                                     // 0x020 0x038
} SYSTEM_VERIFIER_TRIAGE_INFORMATION, *PSYSTEM_VERIFIER_TRIAGE_INFORMATION;
```
