# PROCESS_MITIGATION_IMAGE_LOAD_POLICY

```C
typedef struct _PROCESS_MITIGATION_IMAGE_LOAD_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD NoRemoteImages : 1;
         DWORD NoLowMandatoryLabelImages : 1;
         DWORD PreferSystem32Images : 1;
         DWORD AuditNoRemoteImages : 1;
         DWORD AuditNoLowMandatoryLabelImages : 1;
         DWORD ReservedFlags : 27;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_IMAGE_LOAD_POLICY, *PPROCESS_MITIGATION_IMAGE_LOAD_POLICY;
```
