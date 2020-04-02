# SYSTEM_REF_TRACE_INFORMATION

```C
typedef struct _SYSTEM_REF_TRACE_INFORMATION { // x86 = 20, x64 = 40
   BOOLEAN        TraceEnable;                                  // 0x000 0x000
   BOOLEAN        TracePermanent;                               // 0x001 0x001
   UNICODE_STRING TraceProcessName;                             // 0x004 0x008
   UNICODE_STRING TracePoolTags;                                // 0x00c 0x018
} SYSTEM_REF_TRACE_INFORMATION, *PSYSTEM_REF_TRACE_INFORMATION;
```
