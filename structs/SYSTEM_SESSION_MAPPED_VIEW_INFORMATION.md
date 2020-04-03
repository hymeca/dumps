# SYSTEM_SESSION_MAPPED_VIEW_INFORMATION

```C
typedef struct _SYSTEM_SESSION_MAPPED_VIEW_INFORMATION { // x86 = 20, x64 = 32
   ULONG_PTR NextEntryOffset;                                             // 0x000 0x000
   ULONG     SessionId;                                                   // 0x004 0x008
   ULONG     ViewFailures;                                                // 0x008 0x00c
   SIZE_T    NumberOfBytesAvailable;                                      // 0x00c 0x010
   SIZE_T    NumberOfBytesAvailableConous;                                // 0x010 0x018
} SYSTEM_SESSION_MAPPED_VIEW_INFORMATION, *PSYSTEM_SESSION_MAPPED_VIEW_INFORMATION;
```
