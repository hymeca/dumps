# SYSTEM_VHD_BOOT_INFORMATION

```C
typedef struct _SYSTEM_VHD_BOOT_INFORMATION { // same size in both x86 and x64
   BOOLEAN OsDiskIsVhd;                                                         // 0x000 0x000
   ULONG   OsVhdFilePathOffset;                                                 // 0x004 0x004
   WCHAR   OsVhdParentVolume[1];                                                // 0x008 0x008
} SYSTEM_VHD_BOOT_INFORMATION, *PSYSTEM_VHD_BOOT_INFORMATION;
```
