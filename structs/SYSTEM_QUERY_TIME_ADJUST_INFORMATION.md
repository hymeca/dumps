# SYSTEM_QUERY_TIME_ADJUST_INFORMATION

```C
typedef struct _SYSTEM_QUERY_TIME_ADJUST_INFORMATION { // same size in both x86 and x64
   ULONG   TimeAdjustment;                                                      // 0x000 0x000
   ULONG   TimeIncrement;                                                       // 0x004 0x004
   BOOLEAN Enable;                                                              // 0x008 0x008
} SYSTEM_QUERY_TIME_ADJUST_INFORMATION, *PSYSTEM_QUERY_TIME_ADJUST_INFORMATION;
```
