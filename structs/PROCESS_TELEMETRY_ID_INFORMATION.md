# PROCESS_TELEMETRY_ID_INFORMATION

```C
typedef struct _PROCESS_TELEMETRY_ID_INFORMATION { // same size in both x86 and x64
   ULONG     HeaderSize;                                                      // 0x000 0x000
   ULONG     ProcessId;                                                       // 0x004 0x004
   ULONGLONG ProcessStartKey;                                                 // 0x008 0x008
   ULONGLONG CreateTime;                                                      // 0x010 0x010
   ULONGLONG CreateInterruptTime;                                             // 0x018 0x018
   ULONGLONG CreateUnbiasedInterruptTime;                                     // 0x020 0x020
   ULONGLONG ProcessSequenceNumber;                                           // 0x028 0x028
   ULONGLONG SessionCreateTime;                                               // 0x030 0x030
   ULONG     SessionId;                                                       // 0x038 0x038
   ULONG     BootId;                                                          // 0x03c 0x03c
   ULONG     ImageChecksum;                                                   // 0x040 0x040
   ULONG     ImageTimeDateStamp;                                              // 0x044 0x044
   ULONG     UserSidOffset;                                                   // 0x048 0x048
   ULONG     ImagePathOffset;                                                 // 0x04c 0x04c
   ULONG     PackageNameOffset;                                               // 0x050 0x050
   ULONG     RelativeAppNameOffset;                                           // 0x054 0x054
   ULONG     CommandLineOffset;                                               // 0x058 0x058
} PROCESS_TELEMETRY_ID_INFORMATION, *PPROCESS_TELEMETRY_ID_INFORMATION;
```
