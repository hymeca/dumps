# PROCESS_UICONTEXT_INFORMATION

```C
typedef struct { // same size in both x86 and x64
   PROCESS_UICONTEXT processUIContext;        // 0x000 0x000
   PROCESS_UI_FLAGS  flags;                   // 0x004 0x004
} PROCESS_UICONTEXT_INFORMATION;
```
