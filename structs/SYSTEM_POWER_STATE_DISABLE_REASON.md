# SYSTEM_POWER_STATE_DISABLE_REASON

```C
typedef struct _SYSTEM_POWER_STATE_DISABLE_REASON { // same size in both x86 and x64
   BOOLEAN AffectedState[8];                                                    // 0x000 0x000
   ULONG   PowerReasonCode;                                                     // 0x008 0x008
   ULONG   PowerReasonLength;                                                   // 0x00c 0x00c
} SYSTEM_POWER_STATE_DISABLE_REASON, *PSYSTEM_POWER_STATE_DISABLE_REASON;
```
