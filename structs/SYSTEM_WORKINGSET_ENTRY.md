# SYSTEM_WORKINGSET_ENTRY

```C
typedef struct _SYSTEM_WORKINGSET_ENTRY { // x86 = 20, x64 = 40
   union {
      ULONG  UniqueProcessId;                              // 0x000 0x000
      ULONG  SessionId;                                    // 0x000 0x000
   } DUMMYUNIONNAME;
   SIZE_T WorkingSetPageCount;                             // 0x004 0x008
   SIZE_T CommitPageCount;                                 // 0x008 0x010
   SIZE_T PagedPoolPageCount;                              // 0x00c 0x018
   SIZE_T VirtualSizeInPages;                              // 0x00c 0x018
   SIZE_T PrivateWorkingSetPageCount;                      // 0x010 0x020
} SYSTEM_WORKINGSET_ENTRY, *PSYSTEM_WORKINGSET_ENTRY;
```
