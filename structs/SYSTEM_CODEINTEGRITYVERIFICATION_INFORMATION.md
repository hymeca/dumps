# SYSTEM_CODEINTEGRITYVERIFICATION_INFORMATION

```C
typedef struct _SYSTEM_CODEINTEGRITYVERIFICATION_INFORMATION { // x86 = 12, x64 = 24
   HANDLE FileHandle;                                                         // 0x000 0x000
   ULONG  ImageSize;                                                          // 0x004 0x008
   PVOID  Image;                                                              // 0x008 0x010
} SYSTEM_CODEINTEGRITYVERIFICATION_INFORMATION, *PSYSTEM_CODEINTEGRITYVERIFICATION_INFORMATION;
```
