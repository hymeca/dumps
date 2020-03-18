# RTL_HEAP_ENTRY

```C
typedef struct _RTL_HEAP_ENTRY { // x86 = 16, x64 = 32
   SIZE_T          Size;                                           // 0x000 0x000
   USHORT          Flags;                                          // 0x004 0x008
   USHORT          AllocatorBackTraceIndex;                        // 0x006 0x00a
   union {                                                         // 0x008 0x010 (<unnamed-type-u>)
      struct {                                                     // 0x000 0x000 (::<unnamed-type-s1>)
         SIZE_T Settable;                                          // 0x000 0x000
         ULONG  Tag;                                               // 0x004 0x008
      } s1;
      struct {                                                     // 0x000 0x000 (::<unnamed-type-s2>)
         SIZE_T CommittedSize;                                     // 0x000 0x000
         PVOID  FirstBlock;                                        // 0x004 0x008
      } s2;
   } u;
} RTL_HEAP_ENTRY, *PRTL_HEAP_ENTRY;
```
