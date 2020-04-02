# SYSTEM_SECUREBOOT_PLATFORM_MANIFEST_INFORMATION

```C
typedef struct _SYSTEM_SECUREBOOT_PLATFORM_MANIFEST_INFORMATION { // same size in both x86 and x64
   ULONG PlatformManifestSize;                                                // 0x000 0x000
   UCHAR PlatformManifest[1];                                                 // 0x004 0x004
} SYSTEM_SECUREBOOT_PLATFORM_MANIFEST_INFORMATION, *PSYSTEM_SECUREBOOT_PLATFORM_MANIFEST_INFORMATION;
```
