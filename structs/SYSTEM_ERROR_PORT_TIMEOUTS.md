# SYSTEM_ERROR_PORT_TIMEOUTS

```C
typedef struct _SYSTEM_ERROR_PORT_TIMEOUTS { // same size in both x86 and x64
   ULONG StartTimeout;                                                        // 0x000 0x000
   ULONG CommTimeout;                                                         // 0x004 0x004
} SYSTEM_ERROR_PORT_TIMEOUTS, *PSYSTEM_ERROR_PORT_TIMEOUTS;
```
