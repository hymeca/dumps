# PROCESS_MITIGATION_SIDE_CHANNEL_ISOLATION_POLICY

```C
typedef struct _PROCESS_MITIGATION_SIDE_CHANNEL_ISOLATION_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD SmtBranchTargetIsolation : 1;
         DWORD IsolateSecurityDomain : 1;
         DWORD DisablePageCombine : 1;
         DWORD SpeculativeStoreBypassDisable : 1;
         DWORD ReservedFlags : 28;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_SIDE_CHANNEL_ISOLATION_POLICY, *PPROCESS_MITIGATION_SIDE_CHANNEL_ISOLATION_POLICY;
```
