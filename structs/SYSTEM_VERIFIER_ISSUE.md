# SYSTEM_VERIFIER_ISSUE

```C
typedef struct _SYSTEM_VERIFIER_ISSUE { // x86 = 16, x64 = 32
   ULONG_PTR IssueType;                                  // 0x000 0x000
   PVOID     Address;                                    // 0x004 0x008
   ULONG_PTR Parameters[2];                              // 0x008 0x010
} SYSTEM_VERIFIER_ISSUE, *PSYSTEM_VERIFIER_ISSUE;
```
