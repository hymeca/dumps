# SYSTEM_FIRMWARE_TABLE_HANDLER

```C
/*
typedef NTSTATUS (__cdecl *PFNFTH)(
   _Inout_ PSYSTEM_FIRMWARE_TABLE_INFORMATION SystemFirmwareTableInfo
);
*/
typedef struct _SYSTEM_FIRMWARE_TABLE_HANDLER { // x86 = 16, x64 = 24
   ULONG   ProviderSignature;                                    // 0x000 0x000
   BOOLEAN Register;                                             // 0x004 0x004
   PFNFTH  FirmwareTableHandl                                    // 0x008 0x008
   PVOID   DriverObject;                                         // 0x00c 0x010
} SYSTEM_FIRMWARE_TABLE_HANDLER, *PSYSTEM_FIRMWARE_TABLE_HANDLER;
```
