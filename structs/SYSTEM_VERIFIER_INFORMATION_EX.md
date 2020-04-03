# SYSTEM_VERIFIER_INFORMATION_EX

```C
typedef struct _SYSTEM_VERIFIER_INFORMATION_EX { // x86 = 36, x64 = 40
   ULONG          VerifyMode;                                     // 0x000 0x000
   ULONG          OptionChanges;                                  // 0x004 0x004
   UNICODE_STRING PreviousBucketName;                             // 0x008 0x008
   ULONG          IrpCancelTimeoutMsec;                           // 0x010 0x018
   ULONG          VerifierExtensionEnabled;                       // 0x014 0x01c
   ULONG          Reserved[1];                                    // 0x018 0x020
} SYSTEM_VERIFIER_INFORMATION_EX, *PSYSTEM_VERIFIER_INFORMATION_EX;
```
