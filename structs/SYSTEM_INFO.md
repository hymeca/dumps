# SYSTEM_INFO

```C
typedef struct _SYSTEM_INFO { // x86 = 36, x64 = 48
   union {
      DWORD   dwOemId;                                     // 0x000 0x000
      struct {
         WORD wProcessorArchitecture;                      // 0x000 0x000
         WORD wReserved;                                   // 0x002 0x002
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
   DWORD      dwPageSize;                                  // 0x004 0x004
   LPVOID     lpMinimumApplicationAddress;                 // 0x008 0x008
   LPVOID     lpMaximumApplicationAddress;                 // 0x00c 0x010
   DWORD_PTR  dwActiveProcessorMask;                       // 0x010 0x018
   DWORD      dwNumberOfProcessors;                        // 0x014 0x020
   DWORD      dwProcessorType;                             // 0x018 0x024
   DWORD      dwAllocationGranularity;                     // 0x01c 0x028
   WORD       wProcessorLevel;                             // 0x020 0x02c
   WORD       wProcessorRevision;                          // 0x022 0x02e
} SYSTEM_INFO, *LPSYSTEM_INFO;
```
