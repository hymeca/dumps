# SYSTEM_PROCESSOR_POLICY_INFORMATION

```C
typedef struct _SYSTEM_PROCESSOR_POLICY_INFORMATION { // same size in both x86 and x64
   ULONG        Length;                                                       // 0x000 0x000
   ULONG        PolicyId;                                                     // 0x004 0x004
   XSAVE_POLICY Policy;                                                       // 0x008 0x008
} SYSTEM_PROCESSOR_POLICY_INFORMATION, *PSYSTEM_PROCESSOR_POLICY_INFORMATION;
```
