# PROCESS_MITIGATION_STRICT_HANDLE_CHECK_POLICY

```C
typedef struct _PROCESS_MITIGATION_STRICT_HANDLE_CHECK_POLICY { // same size in both x86 and x64
   union {
      DWORD Flags;
      struct {
         DWORD RaiseExceptionOnInvalidHandleReference : 1;
         DWORD HandleExceptionsPermanentlyEnabled : 1;
         DWORD ReservedFlags : 30;
      } DUMMYSTRUCTNAME;
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_STRICT_HANDLE_CHECK_POLICY, *PPROCESS_MITIGATION_STRICT_HANDLE_CHECK_POLICY;
```
