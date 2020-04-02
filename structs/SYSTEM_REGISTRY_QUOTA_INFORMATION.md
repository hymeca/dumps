# SYSTEM_REGISTRY_QUOTA_INFORMATION

```C
typedef struct _SYSTEM_REGISTRY_QUOTA_INFORMATION { // x86 = 12, x64 = 16
   ULONG  RegistryQuotaAllowed;                                               // 0x000 0x000
   ULONG  RegistryQuotaUsed;                                                  // 0x004 0x004
   SIZE_T PagedPoolSize;                                                      // 0x008 0x008
} SYSTEM_REGISTRY_QUOTA_INFORMATION, *PSYSTEM_REGISTRY_QUOTA_INFORMATION;
```
