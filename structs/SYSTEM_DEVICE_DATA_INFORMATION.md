# SYSTEM_DEVICE_DATA_INFORMATION

```C
typedef struct _SYSTEM_DEVICE_DATA_INFORMATION { // x86 = 28, x64 = 48
   UNICODE_STRING DeviceId;                                       // 0x000 0x000
   UNICODE_STRING DataName;                                       // 0x008 0x010
   ULONG          DataType;                                       // 0x010 0x020
   ULONG          DataBufferLength;                               // 0x014 0x024
   PVOID          DataBuffer;                                     // 0x018 0x028
} SYSTEM_DEVICE_DATA_INFORMATION, *PSYSTEM_DEVICE_DATA_INFORMATION;
```
