# SYSTEM_HOT_PATCH_REGISTRY_VALUE

```C
typedef struct _SYSTEM_HOT_PATCH_REGISTRY_VALUE { // same size in both x86 and x64
   USHORT ImageNameLength;                                                    // 0x000 0x000
   WCHAR  ImageName[1];                                                       // 0x002 0x002
} SYSTEM_HOT_PATCH_REGISTRY_VALUE, *PSYSTEM_HOT_PATCH_REGISTRY_VALUE;
```
