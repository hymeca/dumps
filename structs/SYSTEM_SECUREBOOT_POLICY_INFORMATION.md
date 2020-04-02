# SYSTEM_SECUREBOOT_POLICY_INFORMATION

```C
typedef struct _SYSTEM_SECUREBOOT_POLICY_INFORMATION { // same size in both x86 and x64
   GUID  PolicyPublisher;                                                     // 0x000 0x000
   ULONG PolicyVersion;                                                       // 0x010 0x010
   ULONG PolicyOptions;                                                       // 0x014 0x014
} SYSTEM_SECUREBOOT_POLICY_INFORMATION, *PSYSTEM_SECUREBOOT_POLICY_INFORMATION;
```
