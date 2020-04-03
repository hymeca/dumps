# SYSTEM_THREAD_CID_PRIORITY_INFORMATION

```C
typedef struct _SYSTEM_THREAD_CID_PRIORITY_INFORMATION { // x86 = 12, x64 = 24
   CLIENT_ID ClientId;                                                   // 0x000 0x000
   KPRIORITY Priority;                                                   // 0x008 0x010
} SYSTEM_THREAD_CID_PRIORITY_INFORMATION, *PSYSTEM_THREAD_CID_PRIORITY_INFORMATION;
```
