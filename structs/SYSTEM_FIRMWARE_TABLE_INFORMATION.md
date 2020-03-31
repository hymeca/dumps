# SYSTEM_FIRMWARE_TABLE_INFORMATION

```C
typedef struct _SYSTEM_FIRMWARE_TABLE_INFORMATION { // same size in both x86 and x64
   ULONG                        ProviderSignature;                            // 0x000 0x000
   SYSTEM_FIRMWARE_TABLE_ACTION Action;                                       // 0x004 0x004
   ULONG                        TableID;                                      // 0x008 0x008
   ULONG                        TableBufferLength;                            // 0x00c 0x00c
   UCHAR                        TableBuffer[1];                               // 0x010 0x010
} SYSTEM_FIRMWARE_TABLE_INFORMATION, *PSYSTEM_FIRMWARE_TABLE_INFORMATION;
```
