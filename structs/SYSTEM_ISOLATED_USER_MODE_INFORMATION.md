# SYSTEM_ISOLATED_USER_MODE_INFORMATION

```C
typedef struct _SYSTEM_ISOLATED_USER_MODE_INFORMATION { // same size in both x86 and x64
   BOOLEAN   SecureKernelRunning : 1;                                         // 0x000 0x000
   BOOLEAN   HvciEnabled : 1;                                                 // 0x000 0x000
   BOOLEAN   HvciStrictMode : 1;                                              // 0x000 0x000
   BOOLEAN   DebugEnabled : 1;                                                // 0x000 0x000
   BOOLEAN   FirmwarePageProtection : 1;                                      // 0x000 0x000
   BOOLEAN   EncryptionKeyAvailable : 1;                                      // 0x000 0x000
   BOOLEAN   SpareFlags : 2;                                                  // 0x000 0x000
   BOOLEAN   TrustletRunning : 1;                                             // 0x001 0x001
   BOOLEAN   HvciDisableAllowed : 1;                                          // 0x001 0x001
   BOOLEAN   SpareFlags2 : 6;                                                 // 0x001 0x001
   BYTE      Spare0[6];                                                       // 0x002 0x002
   ULONGLONG Spare1;                                                          // 0x008 0x008
} SYSTEM_ISOLATED_USER_MODE_INFORMATION, *PSYSTEM_ISOLATED_USER_MODE_INFORMATION;
```
