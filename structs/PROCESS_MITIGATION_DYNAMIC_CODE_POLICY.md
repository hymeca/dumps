# PROCESS_MITIGATION_DYNAMIC_CODE_POLICY

```C
typedef struct _PROCESS_MITIGATION_DYNAMIC_CODE_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD ProhibitDynamicCode : 1;
         DWORD AllowThreadOptOut : 1;
         DWORD AllowRemoteDowngrade : 1;
         DWORD AuditProhibitDynamicCode : 1;
         DWORD ReservedFlags : 28;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_DYNAMIC_CODE_POLICY, *PPROCESS_MITIGATION_DYNAMIC_CODE_POLICY;
```
