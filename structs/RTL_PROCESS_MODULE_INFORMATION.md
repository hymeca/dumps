# RTL_PROCESS_MODULE_INFORMATION

```C
typedef struct _RTL_PROCESS_MODULE_INFORMATION { // x86 = 284, x64 = 296
   HANDLE Section;                                        // 0x000 0x000
   PVOID  MappedBase;                                     // 0x004 0x008
   PVOID  ImageBase;                                      // 0x008 0x010
   ULONG  ImageSize;                                      // 0x00c 0x018
   ULONG  Flags;                                          // 0x010 0x01c
   USHORT LoadOrderIndex;                                 // 0x014 0x020
   USHORT InitOrderIndex;                                 // 0x016 0x022
   USHORT LoadCount;                                      // 0x018 0x024
   USHORT OffsetToFileName;                               // 0x01a 0x026
   UCHAR  FullPathName[256];                              // 0x01c 0x028
} RTL_PROCESS_MODULE_INFORMATION, *PRTL_PROCESS_MODULE_INFORMATION;
```
