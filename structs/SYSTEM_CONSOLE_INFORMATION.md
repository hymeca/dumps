# SYSTEM_CONSOLE_INFORMATION

```C
typedef struct _SYSTEM_CONSOLE_INFORMATION { // same size in both x86 and x64
    ULONG DriverLoaded : 1;                                               // 0x000 0x000
    ULONG Spare : 31;                                                     // 0x000 0x000
} SYSTEM_CONSOLE_INFORMATION, *PSYSTEM_CONSOLE_INFORMATION;
```
