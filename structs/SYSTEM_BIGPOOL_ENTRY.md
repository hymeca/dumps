# SYSTEM_BIGPOOL_ENTRY

```C
typedef struct _SYSTEM_BIGPOOL_ENTRY { // x86 = 12, x64 = 24
   union {
      PVOID     VirtualAddress;                         // 0x000 0x000
      ULONG_PTR NonPaged : 1;                           // 0x000 0x000
   };
   SIZE_T       SizeInBytes;                            // 0x004 0x008
   union {
      UCHAR     Tag[4];                                 // 0x008 0x010
      ULONG     TagUlong;                               // 0x008 0x010
   };
} SYSTEM_BIGPOOL_ENTRY, *PSYSTEM_BIGPOOL_ENTRY;
```
