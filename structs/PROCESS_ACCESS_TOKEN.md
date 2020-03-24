# PROCESS_ACCESS_TOKEN

```C
typedef struct _PROCESS_ACCESS_TOKEN { // x86 = 8, x64 = 16
   HANDLE Token;                                          // 0x000 0x000
   HANDLE Thread;                                         // 0x004 0x008
} PROCESS_ACCESS_TOKEN, *PPROCESS_ACCESS_TOKEN;
```
