# RTL_BSD_ITEM

```C
typedef struct _RTL_BSD_ITEM { // x86 = 12, x64 = 24
   RTL_BSD_ITEM_TYPE Type;                                           // 0x000 0x000
   PVOID             DataBuffer;                                     // 0x004 0x008
   ULONG             DataLength;                                     // 0x008 0x010
} RTL_BSD_ITEM, *PRTL_BSD_ITEM;
```
