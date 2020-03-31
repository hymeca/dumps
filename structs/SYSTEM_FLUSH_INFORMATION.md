# SYSTEM_FLUSH_INFORMATION

```C
typedef struct _SYSTEM_FLUSH_INFORMATION { // same size in both x86 and x64
   ULONG     SupportedFlushMethods;                                     // 0x000 0x000
   ULONG     ProcessorCacheFlushSize;                                   // 0x004 0x004
   ULONGLONG SystemFlushCapabilities;                                   // 0x008 0x008
   ULONGLONG Reserved[2];                                               // 0x010 0x010
} SYSTEM_FLUSH_INFORMATION, *PSYSTEM_FLUSH_INFORMATION;
```
