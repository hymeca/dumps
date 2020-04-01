# SYSTEM_POOL_INFORMATION

```C
typedef struct _SYSTEM_POOL_INFORMATION { // x86 = 28, x64 = 40
   SIZE_T            TotalSize;                                     // 0x000 0x000
   PVOID             FirstEntry;                                    // 0x004 0x008
   USHORT            EntryOverhead;                                 // 0x008 0x010
   BOOLEAN           PoolTagPresent;                                // 0x00a 0x012
   BYTE              Spare0;                                        // 0x00b 0x013
   ULONG             NumberOfEntries;                               // 0x00c 0x014
   SYSTEM_POOL_ENTRY Entries[1];                                    // 0x010 0x018
} SYSTEM_POOL_INFORMATION, *PSYSTEM_POOL_INFORMATION;
```
