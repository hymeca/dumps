# SYSTEM_SPECULATION_CONTROL_INFORMATION

```C
typedef struct _SYSTEM_SPECULATION_CONTROL_INFORMATION { // same size in both x86 and x64
   struct {
      ULONG BpbEnabled : 1;
      ULONG BpbDisabledSystemPolicy : 1;
      ULONG BpbDisabledNoHardwareSupport : 1;
      ULONG SpecCtrlEnumerated : 1;
      ULONG SpecCmdEnumerated : 1;
      ULONG IbrsPresent : 1;
      ULONG StibpPresent : 1;
      ULONG SmepPresent : 1;
      ULONG SpeculativeStoreBypassDisableAvailable : 1;
      ULONG SpeculativeStoreBypassDisableSupported : 1;
      ULONG SpeculativeStoreBypassDisabledSystemWide : 1;
      ULONG SpeculativeStoreBypassDisabledKernel : 1;
      ULONG SpeculativeStoreBypassDisableRequired : 1;
      ULONG BpbDisabledKernelToUser : 1;
      ULONG SpecCtrlRetpolineEnabled : 1;
      ULONG SpecCtrlImportOptimizationEnabled : 1;
      ULONG EnhancedIbrs : 1;
      ULONG HvL1tfStatusAvailable : 1;
      ULONG HvL1tfProcessorNotAffected : 1;
      ULONG HvL1tfMigitationEnabled : 1;
      ULONG HvL1tfMigitationNotEnabled_Hardware : 1;
      ULONG HvL1tfMigitationNotEnabled_LoadOption : 1;
      ULONG HvL1tfMigitationNotEnabled_CoreScheduler : 1;
      ULONG EnhancedIbrsReported : 1;
      ULONG MdsHardwareProtected : 1;
      ULONG MbClearEnabled : 1;
      ULONG MbClearReported : 1;
      ULONG TsxCtrlStatus : 2;s
      ULONG TsxCtrlReported : 1;
      ULONG TaaHardwareImmune : 1;
      ULONG Reserved : 1;
   } SpeculationControlFlags;
} SYSTEM_SPECULATION_CONTROL_INFORMATION, *PSYSTEM_SPECULATION_CONTROL_INFORMATION;
```
