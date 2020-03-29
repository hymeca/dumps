# PROCESS_MITIGATION_CHILD_PROCESS_POLICY

```C
typedef struct _PROCESS_MITIGATION_CHILD_PROCESS_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD NoChildProcessCreation : 1;
         DWORD AuditNoChildProcessCreation : 1;
         DWORD AllowSecureProcessCreation : 1;
         DWORD ReservedFlags : 29;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_CHILD_PROCESS_POLICY, *PPROCESS_MITIGATION_CHILD_PROCESS_POLICY;
```
