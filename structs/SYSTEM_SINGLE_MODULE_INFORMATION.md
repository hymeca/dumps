# SYSTEM_SINGLE_MODULE_INFORMATION

```C
typedef struct _SYSTEM_SINGLE_MODULE_INFORMATION { // x86 = 304, x64 = 328
   PVOID                             TargetModuleAddress;            // 0x000 0x000
   RTL_PROCESS_MODULE_INFORMATION_EX ExInfo;                         // 0x004 0x008
} SYSTEM_SINGLE_MODULE_INFORMATION, *PSYSTEM_SINGLE_MODULE_INFORMATION;
```
