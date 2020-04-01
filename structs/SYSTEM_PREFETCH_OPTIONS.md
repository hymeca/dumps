# SYSTEM_PREFETCH_OPTIONS

```C
typedef struct _SYSTEM_PREFETCH_OPTIONS { // same size in both x86 and x64
   union {
      struct {
         ULONG LowerPriority : 1;
         ULONG VirtualOffsets : 1;
         ULONG TrickleIOs : 1;
         ULONG SkipInStorePages : 1;
         ULONG PrefetchFilesByVa : 1;
         ULONG SkipMemoryStorePages : 1;
         ULONG Spare : 2;
         ULONG ScenarioType : 8;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} SYSTEM_PREFETCH_OPTIONS, *PSYSTEM_PREFETCH_OPTIONS;
```
