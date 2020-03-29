# PROCESS_MITIGATION_PAYLOAD_RESTRICTION_POLICY

```C
typedef struct _PROCESS_MITIGATION_PAYLOAD_RESTRICTION_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD EnableExportAddressFilter : 1;
         DWORD AuditExportAddressFilter : 1;
         DWORD EnableExportAddressFilterPlus : 1;
         DWORD AuditExportAddressFilterPlus : 1;
         DWORD EnableImportAddressFilter : 1;
         DWORD AuditImportAddressFilter : 1;
         DWORD EnableRopStackPivot : 1;
         DWORD AuditRopStackPivot : 1;
         DWORD EnableRopCallerCheck : 1;
         DWORD AuditRopCallerCheck : 1;
         DWORD EnableRopSimExec : 1;
         DWORD AuditRopSimExec : 1;
         DWORD ReservedFlags : 20;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_PAYLOAD_RESTRICTION_POLICY, *PPROCESS_MITIGATION_PAYLOAD_RESTRICTION_POLICY;
```
