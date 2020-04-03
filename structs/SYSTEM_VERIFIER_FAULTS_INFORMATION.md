# SYSTEM_VERIFIER_FAULTS_INFORMATION

```C
typedef struct _SYSTEM_VERIFIER_FAULTS_INFORMATION { // x86 = 24, x64 = 40
   ULONG          Probability;                                        // 0x000 0x000
   ULONG          MaxProbability;                                     // 0x004 0x004
   UNICODE_STRING PoolTags;                                           // 0x008 0x008
   UNICODE_STRING Applications;                                       // 0x010 0x018
} SYSTEM_VERIFIER_FAULTS_INFORMATION, *PSYSTEM_VERIFIER_FAULTS_INFORMATION;
```
