# SYSTEM_CODEINTEGRITYPOLICY_INFORMATION

```C
typedef struct _SYSTEM_CODEINTEGRITYPOLICY_INFORMATION { // same size in both x86 and x64
   ULONG     Options;                                                         // 0x000 0x000
   ULONG     HVCIOptions;                                                     // 0x004 0x004
   ULONGLONG Version;                                                         // 0x008 0x008
   GUID      PolicyGuid;                                                      // 0x010 0x010
} SYSTEM_CODEINTEGRITYPOLICY_INFORMATION, *PSYSTEM_CODEINTEGRITYPOLICY_INFORMATION;
```
