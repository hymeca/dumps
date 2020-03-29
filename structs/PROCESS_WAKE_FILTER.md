# PROCESS_WAKE_FILTER

```C
typedef struct { // same size in both x86 and x64
   ULONG HighEdgeFilter;                                                      // 0x000 0x000
   ULONG LowEdgeFilter;                                                       // 0x004 0x004
} PROCESS_WAKE_FILTER;
```
