# SYSTEM_REGISTRY_APPEND_STRING_PARAMETERS

```C
typedef struct _SYSTEM_REGISTRY_APPEND_STRING_PARAMETERS { // x86 = 36, x64 = 56
   HANDLE          KeyHandle;                                               // 0x000 0x000
   PUNICODE_STRING ValueNamePointer;                                        // 0x004 0x008
   PULONG          RequiredLengthPointer;                                   // 0x008 0x010
   PUCHAR          Buffer;                                                  // 0x00c 0x018
   ULONG           BufferLength;                                            // 0x010 0x020
   ULONG           Type;                                                    // 0x014 0x024
   PUCHAR          AppendBuffer;                                            // 0x018 0x028
   ULONG           AppendBufferLength;                                      // 0x01c 0x030
   BOOLEAN         CreateIfDoesntExist;                                     // 0x020 0x034
   BOOLEAN         TruncateExistingValue;                                   // 0x021 0x035
} SYSTEM_REGISTRY_APPEND_STRING_PARAMETERS, *PSYSTEM_REGISTRY_APPEND_STRING_PARAMETERS;
```
