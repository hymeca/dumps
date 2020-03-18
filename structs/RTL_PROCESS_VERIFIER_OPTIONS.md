# RTL_PROCESS_VERIFIER_OPTIONS

```C
typedef struct _RTL_PROCESS_VERIFIER_OPTIONS { // same size in both x86 and x64
   ULONG SizeStruct;                                     // 0x000 0x000
   ULONG Option;                                         // 0x004 0x004
   UCHAR OptionData[1];                                  // 0x008 0x008
} RTL_PROCESS_VERIFIER_OPTIONS, *PRTL_PROCESS_VERIFIER_OPTIONS;
```
