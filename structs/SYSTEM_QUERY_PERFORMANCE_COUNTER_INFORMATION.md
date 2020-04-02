# SYSTEM_QUERY_PERFORMANCE_COUNTER_INFORMATION

```C
typedef struct _SYSTEM_QUERY_PERFORMANCE_COUNTER_INFORMATION { // same size in both x86 and x64
   ULONG                           Version;                                   // 0x000 0x000
   QUERY_PERFORMANCE_COUNTER_FLAGS Flags;                                     // 0x004 0x004
   QUERY_PERFORMANCE_COUNTER_FLAGS ValidFlags;                                // 0x008 0x008
} SYSTEM_QUERY_PERFORMANCE_COUNTER_INFORMATION, *PSYSTEM_QUERY_PERFORMANCE_COUNTER_INFORMATION;
```
