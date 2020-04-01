# SYSTEM_MEMORY_INFORMATION

```C
typedef struct _SYSTEM_MEMORY_INFORMATION { // x86 = 16, x64 = 32
   SIZE_T PagedPoolCommitPageCount;                                        // 0x000 0x000
   SIZE_T NonPagedPoolPageCount;                                           // 0x004 0x008
   SIZE_T MdlPageCount;                                                    // 0x008 0x010
   SIZE_T CommitPageCount;                                                 // 0x00c 0x018
} SYSTEM_MEMORY_INFORMATION, *PSYSTEM_MEMORY_INFORMATION;
```
