# SYSTEM_MEMORY_LIST_INFORMATION

```C
typedef struct _SYSTEM_MEMORY_LIST_INFORMATION { // x86 = 88, x64 = 176
   SIZE_T ZeroPageCount;                                                   // 0x000 0x000
   SIZE_T FreePageCount;                                                   // 0x004 0x008
   SIZE_T ModifiedPageCount;                                               // 0x008 0x010
   SIZE_T ModifiedNoWritePageCount;                                        // 0x00c 0x018
   SIZE_T BadPageCount;                                                    // 0x010 0x020
   SIZE_T PageCountByPriority[8];                                          // 0x014 0x028
   SIZE_T RepurposedPagesByPriority[8];                                    // 0x034 0x068
   SIZE_T ModifiedPageCountPageFile;                                       // 0x054 0x0a8
} SYSTEM_MEMORY_LIST_INFORMATION, *PSYSTEM_MEMORY_LIST_INFORMATION;
```
