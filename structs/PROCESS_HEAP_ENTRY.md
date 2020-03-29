# PROCESS_HEAP_ENTRY

```C
typedef struct _PROCESS_HEAP_ENTRY { // x86 = 28, x64 = 40
   PVOID        lpData;                               // 0x000 0x000
   DWORD        cbData;                               // 0x004 0x008
   BYTE         cbOverhead;                           // 0x008 0x00c
   BYTE         iRegionIndex;                         // 0x009 0x00d
   WORD         wFlags;                               // 0x00a 0x00e
   union {                                            // 0x00c 0x010
      struct {
         HANDLE hMem;                                 // 0x000 0x000
         DWORD  dwReserved[3];                        // 0x004 0x008
      } Block;

      struct {
         DWORD  dwCommittedSize;                      // 0x000 0x000
         DWORD  dwUnCommittedSize;                    // 0x004 0x004
         LPVOID lpFirstBlock;                         // 0x008 0x008
         LPVOID lpLastBlock;                          // 0x00c 0x010
      } Region;
   };
} PROCESS_HEAP_ENTRY, *LPPROCESS_HEAP_ENTRY, *PPROCESS_HEAP_ENTRY;
```
