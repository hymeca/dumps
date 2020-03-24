# RTL_BUFFER

```C
typedef struct _RTL_BUFFER { // x86 = 16, x64 = 32
   PUCHAR Buffer;                                         // 0x000 0x000
   PUCHAR StaticBuffer;                                   // 0x004 0x008
   SIZE_T Size;                                           // 0x008 0x010
   SIZE_T StaticSize;                                     // 0x00c 0x018
} RTL_BUFFER, *PRTL_BUFFER;
```
