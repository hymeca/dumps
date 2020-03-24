# PROCESS_AFFINITY_UPDATE_MODE

```C
typedef union _PROCESS_AFFINITY_UPDATE_MODE { // same size in both x86 and x64
   ULONG    Flags;                                          // 0x000 0x000
   struct {
      ULONG EnableAutoUpdate : 1;                           // 0x000 0x000
      ULONG Permanent : 1;                                  // 0x000 0x000
      ULONG Reserved : 30;                                  // 0x000 0x000
   };
} PROCESS_AFFINITY_UPDATE_MODE, *PPROCESS_AFFINITY_UPDATE_MODE;
```
