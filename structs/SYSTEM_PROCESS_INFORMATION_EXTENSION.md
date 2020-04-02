# SYSTEM_PROCESS_INFORMATION_EXTENSION

```C
typedef struct _SYSTEM_PROCESS_INFORMATION_EXTENSION { // x86 = 360, x64 = 368
   PROCESS_DISK_COUNTERS DiskCounters;                                   // 0x000 0x000
   ULONGLONG             ContextSwitches;                                // 0x028 0x028
   union {
      ULONG              Flags;                                          // 0x030 0x030
      struct {
         ULONG           HasStrongId : 1;                                // 0x030 0x030
         ULONG           Classification : 4;                             // 0x030 0x030
         ULONG           BackgroundActivityModerated : 1;                // 0x030 0x030
         ULONG           Spare : 26;                                     // 0x030 0x030
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
   ULONG                 UserSidOffset;                                  // 0x034 0x034
   ULONG                 PackageFullNameOffset;                          // 0x038 0x038
   PROCESS_ENERGY_VALUES EnergyValues;                                   // 0x040 0x040
   ULONG                 AppIdOffset;                                    // 0x150 0x150
   SIZE_T                SharedCommitCharge;                             // 0x154 0x158
   ULONG                 JobObjectId;                                    // 0x158 0x160
   ULONG                 SpareUlong;                                     // 0x15c 0x164
   ULONGLONG             ProcessSequenceNumber;                          // 0x160 0x168
} SYSTEM_PROCESS_INFORMATION_EXTENSION, *PSYSTEM_PROCESS_INFORMATION_EXTENSION;
```
