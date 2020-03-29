# PROCESS_WAKE_INFORMATION

```C
typedef struct _PROCESS_WAKE_INFORMATION { // same size in both x86 and x64
   ULONGLONG             NotificationChannel;                           // 0x000 0x000
   ULONG                 WakeCounters[7];                               // 0x008 0x008
   JOBOBJECT_WAKE_FILTER WakeFilter;                                    // 0x024 0x024
} PROCESS_WAKE_INFORMATION, *PPROCESS_WAKE_INFORMATION;
```
