# PROCESS_POWER_THROTTLING_STATE

```C
typedef struct _PROCESS_POWER_THROTTLING_STATE { // same size in both x86 and x64
   ULONG Version;                                                             // 0x000 0x000
   ULONG ControlMask;                                                         // 0x004 0x004
   ULONG StateMask;                                                           // 0x008 0x008
} PROCESS_POWER_THROTTLING_STATE, *PPROCESS_POWER_THROTTLING_STATE;
```
