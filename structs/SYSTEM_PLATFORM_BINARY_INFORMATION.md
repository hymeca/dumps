# SYSTEM_PLATFORM_BINARY_INFORMATION

```C
typedef struct _SYSTEM_PLATFORM_BINARY_INFORMATION { // x86 = 24, x64 = 32
   ULONGLONG PhysicalAddress;                                         // 0x000 0x000
   PVOID     HandoffBuffer;                                           // 0x008 0x008
   PVOID     CommandLineBuffer;                                       // 0x00c 0x010
   ULONG     HandoffBufferSize;                                       // 0x010 0x018
   ULONG     CommandLineBufferSize;                                   // 0x014 0x01c
} SYSTEM_PLATFORM_BINARY_INFORMATION, *PSYSTEM_PLATFORM_BINARY_INFORMATION;
```
