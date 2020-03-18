# UNICODE_STRING

```C
typedef struct _UNICODE_STRING { // x86 = 8, x64 = 16
   USHORT Length;                                         // 0x000 0x000
   USHORT MaximumLength;                                  // 0x002 0x002
   PWSTR  Buffer;                                         // 0x004 0x008
} UNICODE_STRING, *PUNICODE_STRING;
```
