# PROCESS_MITIGATION_BINARY_SIGNATURE_POLICY

```C
typedef struct _PROCESS_MITIGATION_BINARY_SIGNATURE_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD MicrosoftSignedOnly : 1;
         DWORD StoreSignedOnly : 1;
         DWORD MitigationOptIn : 1;
         DWORD AuditMicrosoftSignedOnly : 1;
         DWORD AuditStoreSignedOnly : 1;
         DWORD ReservedFlags : 27;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_BINARY_SIGNATURE_POLICY, *PPROCESS_MITIGATION_BINARY_SIGNATURE_POLICY;
```
