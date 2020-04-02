# SYSTEM_SECUREBOOT_POLICY_FULL_INFORMATION

```C
typedef struct _SYSTEM_SECUREBOOT_POLICY_FULL_INFORMATION { // same size in both x86 and x64
   SYSTEM_SECUREBOOT_POLICY_INFORMATION PolicyInformation;                    // 0x000 0x000
   ULONG                                PolicySize;                           // 0x018 0x018
   UCHAR                                Policy[1];                            // 0x01c 0x01c
} SYSTEM_SECUREBOOT_POLICY_FULL_INFORMATION, *PSYSTEM_SECUREBOOT_POLICY_FULL_INFORMATION;
```
