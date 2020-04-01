# SYSTEM_NET_RATE_CONTROL_SET_CONTEXT

```C
typedef struct _SYSTEM_NET_RATE_CONTROL_SET_CONTEXT { // x86 = 32, x64 = 40
   SYSTEM_NET_RATE_CONTROL_CONTEXT_HEADER Header;                      // 0x000 0x000
   ULONGLONG   MaxBandwidth;                                           // 0x008 0x010
   PGUID       ContainerId;                                            // 0x010 0x018
   union {
      ULONG    Flags;                                                  // 0x014 0x020
      struct {
         ULONG Set : 1;                                                // 0x014 0x020
         ULONG Update : 1;                                             // 0x014 0x020
         ULONG Clear : 1;                                              // 0x014 0x020
         ULONG DscpTagEnabled : 1;                                     // 0x014 0x020
         ULONG MaxBandwidthEnabled : 1;                                // 0x014 0x020
         ULONG Reserved : 27;                                          // 0x014 0x020
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
   UCHAR       DscpTag;                                                // 0x018 0x024
} SYSTEM_NET_RATE_CONTROL_SET_CONTEXT, *PSYSTEM_NET_RATE_CONTROL_SET_CONTEXT;
```
