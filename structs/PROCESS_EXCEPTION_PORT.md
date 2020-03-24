# PROCESS_EXCEPTION_PORT

```C
typedef struct _PROCESS_EXCEPTION_PORT { // x86 = 8, x64 = 16
   HANDLE ExceptionPortHandle;                            // 0x000 0x000
   ULONG  StateFlags;                                     // 0x004 0x008
} PROCESS_EXCEPTION_PORT, *PPROCESS_EXCEPTION_PORT;
```
