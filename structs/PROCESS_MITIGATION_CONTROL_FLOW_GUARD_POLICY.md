# PROCESS_MITIGATION_CONTROL_FLOW_GUARD_POLICY

```C
typedef struct _PROCESS_MITIGATION_CONTROL_FLOW_GUARD_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD EnableControlFlowGuard : 1;
         DWORD EnableExportSuppression : 1;
         DWORD StrictMode : 1;
         DWORD ReservedFlags : 29;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_CONTROL_FLOW_GUARD_POLICY, *PPROCESS_MITIGATION_CONTROL_FLOW_GUARD_POLICY;
```
