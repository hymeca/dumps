# SYSTEM_NET_RATE_CONTROL_CONTEXT_HEADER

```C
typedef struct _SYSTEM_NET_RATE_CONTROL_CONTEXT_HEADER { // x86 = 8, x64 = 16
   ULONG_PTR                    PolicyCookie;                            // 0x000 0x000
   SYSTEM_NET_RATE_CONTROL_TYPE Type;                                    // 0x004 0x008
} SYSTEM_NET_RATE_CONTROL_CONTEXT_HEADER, *PSYSTEM_NET_RATE_CONTROL_CONTEXT_HEADER;
```
