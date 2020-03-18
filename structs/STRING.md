# STRING

```C
typedef struct _STRING { // x86 = 8, x64 = 16
   USHORT Length;                                         // 0x000 0x000
   USHORT MaximumLength;                                  // 0x002 0x002
   PSTR   Buffer;                                         // 0x004 0x008
} STRING, *PSTRING;
```
