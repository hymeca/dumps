# SYSTEM_QUERY_TIME_ADJUST_INFORMATION_PRECISE

```C
typedef struct _SYSTEM_QUERY_TIME_ADJUST_INFORMATION_PRECISE { // same size in both x86 and x64
   ULONGLONG TimeAdjustment;                                                  // 0x000 0x000
   ULONGLONG TimeIncrement;                                                   // 0x008 0x008
   BOOLEAN   Enable;                                                          // 0x010 0x010
} SYSTEM_QUERY_TIME_ADJUST_INFORMATION_PRECISE, *PSYSTEM_QUERY_TIME_ADJUST_INFORMATION_PRECISE;
```
