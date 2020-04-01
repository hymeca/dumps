# SYSTEM_PAGEFILE_INFORMATION_EX

```C
typedef struct _SYSTEM_PAGEFILE_INFORMATION_EX { // x86 = 32, x64 = 40
   SYSTEM_PAGEFILE_INFORMATION Info;                              // 0x000 0x000
   ULONG                       MinimumSize;                       // 0x018 0x020
   ULONG                       MaximumSize;                       // 0x01c 0x024
} SYSTEM_PAGEFILE_INFORMATION_EX, *PSYSTEM_PAGEFILE_INFORMATION_EX;
```
