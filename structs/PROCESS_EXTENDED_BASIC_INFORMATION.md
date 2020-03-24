# PROCESS_EXTENDED_BASIC_INFORMATION

```C
typedef struct _PROCESS_EXTENDED_BASIC_INFORMATION { // x86 = 32, x64 = 64
   SIZE_T                    Size;                                           // 0x000 0x000
   PROCESS_BASIC_INFORMATION BasicInfo;                                      // 0x004 0x008
   union {
      ULONG                  Flags;                                          // 0x01c 0x038
      struct {
         ULONG               IsProtectedProcess : 1;                         // 0x01c 0x038
         ULONG               IsWow64Process : 1;                             // 0x01c 0x038
         ULONG               IsProcessDeleting : 1;                          // 0x01c 0x038
         ULONG               IsCrossSessionCreate : 1;                       // 0x01c 0x038
         ULONG               IsFrozen : 1;                                   // 0x01c 0x038
         ULONG               IsBackground : 1;                               // 0x01c 0x038
         ULONG               IsStronglyNamed : 1;                            // 0x01c 0x038
         ULONG               IsSecureProcess : 1;                            // 0x01c 0x038
         ULONG               IsSubsystemProcess : 1;                         // 0x01c 0x038
         ULONG               SpareBits : 23;                                 // 0x01c 0x038
      };
   };
} PROCESS_EXTENDED_BASIC_INFORMATION, *PPROCESS_EXTENDED_BASIC_INFORMATION;
```
