# OLETLS_PREVENT_RUNDOWN_MITIGATION

```C
typedef enum {
   NoMitigationInEffect = 0,
   MarshalingWithInParameterMitigation = 1,
   MarshalingWithInprocOutParameterMitigation = 2,
   MarshalingWithOutofprocOutParameterMitigation = 3,
   MarshalingWithMshlflagsTablestrong = 4,
   UnmarshalingWithInParameterMitigation = 5,
   UnmarshalingWithInprocOutParameterMitigation = 6,
   UnmarshalingWithOutofprocOutParameterMitigation = 7
} OLETLS_PREVENT_RUNDOWN_MITIGATION;
```
