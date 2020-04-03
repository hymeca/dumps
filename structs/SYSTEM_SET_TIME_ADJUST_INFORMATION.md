# SYSTEM_SET_TIME_ADJUST_INFORMATION

```C
typedef struct _SYSTEM_SET_TIME_ADJUST_INFORMATION { // same size in both x86 and x64
   ULONG   TimeAdjustment;                                                      // 0x000 0x000
   BOOLEAN Enable;                                                              // 0x004 0x004
} SYSTEM_SET_TIME_ADJUST_INFORMATION, *PSYSTEM_SET_TIME_ADJUST_INFORMATION;
```
