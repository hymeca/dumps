# PROCESS_WINDOW_INFORMATION

```C
typedef struct _PROCESS_WINDOW_INFORMATION { // same size in both x86 and x64
   ULONG  WindowFlags;                                                    // 0x000 0x000
   USHORT WindowTitleLength;                                              // 0x004 0x004
   WCHAR  WindowTitle[1];                                                 // 0x006 0x006
} PROCESS_WINDOW_INFORMATION, *PPROCESS_WINDOW_INFORMATION;
```
