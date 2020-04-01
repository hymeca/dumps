# SYSTEM_NET_RATE_CONTROL_QUOTA_CONTEXT

```C
typedef struct _SYSTEM_NET_RATE_CONTROL_QUOTA_CONTEXT { // x86 = 24, x64 = 32
   SYSTEM_NET_RATE_CONTROL_CONTEXT_HEADER Header;                        // 0x000 0x000
   ULONGLONG                              OverQuotaHistory;              // 0x008 0x010
   ULONG                                  IntervalLength;                // 0x010 0x018
   ULONG                                  NumberOfIntervals;             // 0x014 0x01c
} SYSTEM_NET_RATE_CONTROL_QUOTA_CONTEXT, *PSYSTEM_NET_RATE_CONTROL_QUOTA_CONTEXT;
```
