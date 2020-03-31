# SYSTEM_DEVICE_INFORMATION

```C
typedef struct _SYSTEM_DEVICE_INFORMATION { // same size in both x86 and x64
   ULONG NumberOfDisks;                                                       // 0x000 0x000
   ULONG NumberOfFloppies;                                                    // 0x004 0x004
   ULONG NumberOfCdRoms;                                                      // 0x008 0x008
   ULONG NumberOfTapes;                                                       // 0x00c 0x00c
   ULONG NumberOfSerialPorts;                                                 // 0x010 0x010
   ULONG NumberOfParallelPorts;                                               // 0x014 0x014
} SYSTEM_DEVICE_INFORMATION, *PSYSTEM_DEVICE_INFORMATION;
```
