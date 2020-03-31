# SYSTEM_GDI_DRIVER_INFORMATION

```C
typedef struct _SYSTEM_GDI_DRIVER_INFORMATION { // x86 = 28, x64 = 56
   UNICODE_STRING          DriverName;                           // 0x000 0x000
   PVOID                   ImageAddress;                         // 0x008 0x010
   PVOID                   SectionPointer;                       // 0x00c 0x018
   PVOID                   EntryPoint;                           // 0x010 0x020
   PIMAGE_EXPORT_DIRECTORY ExportSectionPointer                  // 0x014 0x028
   ULONG                   ImageLength;                          // 0x018 0x030
} SYSTEM_GDI_DRIVER_INFORMATION, *PSYSTEM_GDI_DRIVER_INFORMATION;
```
