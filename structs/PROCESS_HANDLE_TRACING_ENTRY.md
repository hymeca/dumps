# PROCESS_HANDLE_TRACING_ENTRY

```C
typedef struct _PROCESS_HANDLE_TRACING_ENTRY { // x86 = 80, x64 = 160
   HANDLE    Handle;                                            // 0x000 0x000
   CLIENT_ID ClientId;                                          // 0x004 0x008
   ULONG     Type;                                              // 0x00c 0x018
   PVOID     Stacks[16];                                        // 0x010 0x020
} PROCESS_HANDLE_TRACING_ENTRY, *PPROCESS_HANDLE_TRACING_ENTRY;
```
