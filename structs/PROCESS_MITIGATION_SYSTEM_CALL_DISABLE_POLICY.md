# PROCESS_MITIGATION_SYSTEM_CALL_DISABLE_POLICY

```C
typedef struct _PROCESS_MITIGATION_SYSTEM_CALL_DISABLE_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD DisallowWin32kSystemCalls : 1;
         DWORD AuditDisallowWin32kSystemCalls : 1;
         DWORD ReservedFlags : 30;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_SYSTEM_CALL_DISABLE_POLICY, *PPROCESS_MITIGATION_SYSTEM_CALL_DISABLE_POLICY;
```
