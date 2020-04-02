# SYSTEM_ROOT_SILO_INFORMATION

```C
typedef struct _SYSTEM_ROOT_SILO_INFORMATION { // same size in both x86 and x64
   ULONG NumberOfSilos;                                                       // 0x000 0x000
   ULONG SiloIdList[1];                                                       // 0x004 0x004
} SYSTEM_ROOT_SILO_INFORMATION, *PSYSTEM_ROOT_SILO_INFORMATION;
```
