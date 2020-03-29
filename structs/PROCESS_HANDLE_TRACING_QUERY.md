# PROCESS_HANDLE_TRACING_QUERY

```C
typedef struct _PROCESS_HANDLE_TRACING_QUERY { // x86 = 88, x64 = 176
   HANDLE                       Handle;                         // 0x000 0x000
   ULONG                        TotalTraces;                    // 0x004 0x008
   PROCESS_HANDLE_TRACING_ENTRY HandleTrace[1];                 // 0x008 0x010
} PROCESS_HANDLE_TRACING_QUERY, *PPROCESS_HANDLE_TRACING_QUERY;
```
