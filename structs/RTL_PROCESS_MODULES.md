# RTL_PROCESS_MODULES

```C
typedef struct _RTL_PROCESS_MODULES { // x86 = 288, x64 = 304
   ULONG                          NumberOfModules;                                // 0x000 0x000
   RTL_PROCESS_MODULE_INFORMATION Modules[1];                                     // 0x004 0x008
} RTL_PROCESS_MODULES, *PRTL_PROCESS_MODULES;
```
