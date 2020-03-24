# PROCESS_COMMIT_RELEASE_INFORMATION

```C
typedef struct _PROCESS_COMMIT_RELEASE_INFORMATION { // x86 = 20, x64 = 32
   ULONG    Version;                                        // 0x000 0x000
   struct {
      ULONG Eligible : 1;                                   // 0x004 0x004
      ULONG ReleaseRepurposedMemResetCommit : 1;            // 0x004 0x004
      ULONG ForceReleaseMemResetCommit : 1;                 // 0x004 0x004
      ULONG Spare : 29;                                     // 0x004 0x004
   };
   SIZE_T   CommitDebt;                                     // 0x008 0x008
   SIZE_T   CommittedMemResetSize;                          // 0x00c 0x010
   SIZE_T   RepurposedMemResetSize;                         // 0x010 0x018
} PROCESS_COMMIT_RELEASE_INFORMATION, *PPROCESS_COMMIT_RELEASE_INFORMATION;
```
