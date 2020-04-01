# SYSTEM_POWER_LOGGING_ENTRY

```C
typedef struct _SYSTEM_POWER_LOGGING_ENTRY { // same size in both x86 and x64
   ULONG Reason;                                                              // 0x000 0x000
   ULONG States;                                                              // 0x004 0x004
} SYSTEM_POWER_LOGGING_ENTRY, *PSYSTEM_POWER_LOGGING_ENTRY;
```
