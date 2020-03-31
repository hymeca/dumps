# SYSTEM_CODEINTEGRITY_UNLOCK_INFORMATION

```C
typedef struct _SYSTEM_CODEINTEGRITY_UNLOCK_INFORMATION { // same size in both x86 and x64
   union {
      ULONG    Flags;                                                               // 0x000 0x000
      struct {
         ULONG Locked : 1;                                                          // 0x000 0x000
         ULONG UnlockApplied : 1;                                                   // 0x000 0x000
         ULONG UnlockIdValid : 1;                                                   // 0x000 0x000
         ULONG Reserved : 29;                                                       // 0x000 0x000
      };
   };
   UCHAR       UnlockId[32];                                                        // 0x004 0x004
} SYSTEM_CODEINTEGRITY_UNLOCK_INFORMATION, *PSYSTEM_CODEINTEGRITY_UNLOCK_INFORMATION;
```
