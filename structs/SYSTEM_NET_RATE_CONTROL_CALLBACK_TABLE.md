# SYSTEM_NET_RATE_CONTROL_CALLBACK_TABLE

```C
/*
typedef NTSTATUS (__cdecl *PFNNRCD)(
   _Inout_ ???
);
*/
typedef struct _SYSTEM_NET_RATE_CONTROL_CALLBACK_TABLE { // x86 = 4, x64 = 8
   PFNNRCD NetRateControlDispatch;                                       // 0x000 0x000
} SYSTEM_NET_RATE_CONTROL_CALLBACK_TABLE, *PSYSTEM_NET_RATE_CONTROL_CALLBACK_TABLE;
```
