# SYSTEM_BOOT_ENVIRONMENT_INFORMATION

```C
typedef struct _SYSTEM_BOOT_ENVIRONMENT_INFORMATION { // same size in both x86 and x64
   GUID            BootIdentifier;                                              // 0x000 0x000
   FIRMWARE_TYPE   FirmwareType;                                                // 0x010 0x010
   union {
      ULONGLONG    BootFlags;                                                   // 0x018 0x018
      struct {
         ULONGLONG DbgMenuOsSelection : 1;                                      // 0x018 0x018
         ULONGLONG DbgHiberBoot : 1;                                            // 0x018 0x018
         ULONGLONG DbgSoftBoot : 1;                                             // 0x018 0x018
         ULONGLONG DbgMeasuredLaunch : 1;                                       // 0x018 0x018
         ULONGLONG DbgMeasuredLaunchCapable : 1;                                // 0x018 0x018
         ULONGLONG DbgSystemHiveReplace : 1;                                    // 0x018 0x018
         ULONGLONG DbgMeasuredLaunchSmmProtections : 1;                         // 0x018 0x018
      };
   };
} SYSTEM_BOOT_ENVIRONMENT_INFORMATION, *PSYSTEM_BOOT_ENVIRONMENT_INFORMATION;
```
