# SYSTEM_HYPERVISOR_DETAIL_INFORMATION

```C
typedef struct _SYSTEM_HYPERVISOR_DETAIL_INFORMATION { // same size in both x86 and x64
   HV_DETAILS HvVendorAndMaxFunction;                                         // 0x000 0x000
   HV_DETAILS HypervisorInterface;                                            // 0x010 0x010
   HV_DETAILS HypervisorVersion;                                              // 0x020 0x020
   HV_DETAILS HvFeatures;                                                     // 0x030 0x030
   HV_DETAILS HwFeatures;                                                     // 0x040 0x040
   HV_DETAILS EnlightenmentInfo;                                              // 0x050 0x050
   HV_DETAILS ImplementationLimits;                                           // 0x060 0x060
} SYSTEM_HYPERVISOR_DETAIL_INFORMATION, *PSYSTEM_HYPERVISOR_DETAIL_INFORMATION;
```
