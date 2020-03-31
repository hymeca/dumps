# SYSTEM_KERNEL_VA_SHADOW_INFORMATION

```C
typedef struct _SYSTEM_KERNEL_VA_SHADOW_INFORMATION { // same size in both x86 and x64
   union {
      ULONG Flags;
      struct {
         ULONG KvaShadowEnabled : 1;
         ULONG KvaShadowUserGlobal : 1;
         ULONG KvaShadowPcid : 1;
         ULONG KvaShadowInvpcid : 1;
         ULONG KvaShadowRequired : 1;
         ULONG KvaShadowRequiredAvailable : 1;
         ULONG InvalidPteBit : 6;
         ULONG L1DataCacheFlushSupported : 1;
         ULONG L1TerminalFaultMitigationPresent : 1;
         ULONG Reserved : 18;
      } KvaShadowFlags;
   } DUMMYUNIONNAME;
} SYSTEM_KERNEL_VA_SHADOW_INFORMATION, *PSYSTEM_KERNEL_VA_SHADOW_INFORMATION;
```
