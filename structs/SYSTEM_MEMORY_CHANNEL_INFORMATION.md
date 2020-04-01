# SYSTEM_MEMORY_CHANNEL_INFORMATION

```C
typedef struct _SYSTEM_MEMORY_CHANNEL_INFORMATION { // same size in both x86 and x64
   ULONG     ChannelNumber;                                                   // 0x000 0x000
   ULONG     ChannelHeatIndex;                                                // 0x004 0x004
   ULONGLONG TotalPageCount;                                                  // 0x008 0x008
   ULONGLONG ZeroPageCount;                                                   // 0x010 0x010
   ULONGLONG FreePageCount;                                                   // 0x018 0x018
   ULONGLONG StandbyPageCount;                                                // 0x020 0x020
} SYSTEM_MEMORY_CHANNEL_INFORMATION, *PSYSTEM_MEMORY_CHANNEL_INFORMATION;
```
