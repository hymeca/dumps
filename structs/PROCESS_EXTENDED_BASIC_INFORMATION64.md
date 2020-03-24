# PROCESS_EXTENDED_BASIC_INFORMATION64

```C
typedef struct _PROCESS_EXTENDED_BASIC_INFORMATION64 { // same size in both x86 and x64
   ULONGLONG                   Size;                                           // 0x000 0x000
   PROCESS_BASIC_INFORMATION64 BasicInfo;                                      // 0x008 0x008
   union {
      ULONG                    Flags;                                          // 0x038 0x038
      struct {
         ULONG                 IsProtectedProcess : 1;                         // 0x038 0x038
         ULONG                 IsWow64Process : 1;                             // 0x038 0x038
         ULONG                 IsProcessDeleting : 1;                          // 0x038 0x038
         ULONG                 IsCrossSessionCreate : 1;                       // 0x038 0x038
         ULONG                 IsFrozen : 1;                                   // 0x038 0x038
         ULONG                 IsBackground : 1;                               // 0x038 0x038
         ULONG                 IsStronglyNamed : 1;                            // 0x038 0x038
         ULONG                 IsSecureProcess : 1;                            // 0x038 0x038
         ULONG                 IsPicoProcess : 1;                              // 0x038 0x038
         ULONG                 SpareBits : 23;                                 // 0x038 0x038
      };
   };
} PROCESS_EXTENDED_BASIC_INFORMATION64, *PPROCESS_EXTENDED_BASIC_INFORMATION64;
```
