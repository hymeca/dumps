# SYSTEM_SET_TIME_ADJUST_INFORMATION_PRECISE

```C
typedef struct _SYSTEM_SET_TIME_ADJUST_INFORMATION_PRECISE { // same size in both x86 and x64
   ULONGLONG TimeAdjustment;                                                  // 0x000 0x000
   BOOLEAN   Enable;                                                          // 0x008 0x008
} SYSTEM_SET_TIME_ADJUST_INFORMATION_PRECISE, *PSYSTEM_SET_TIME_ADJUST_INFORMATION_PRECISE;
```
