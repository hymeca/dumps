# SYSTEM_SECURITY_MODEL_INFORMATION

```C
typedef struct _SYSTEM_SECURITY_MODEL_INFORMATION { // same size in both x86 and x64
   struct {
      ULONG SModeAdminlessEnabled : 1;
      ULONG AllowDeviceOwnerProtectionDowngrade : 1;
      ULONG Reserved : 30;
   } SecurityModelFlags;
} SYSTEM_SECURITY_MODEL_INFORMATION, *PSYSTEM_SECURITY_MODEL_INFORMATION;
```
