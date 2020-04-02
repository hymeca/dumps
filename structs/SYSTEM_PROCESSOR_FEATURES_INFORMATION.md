# SYSTEM_PROCESSOR_FEATURES_INFORMATION

```C
typedef struct _SYSTEM_PROCESSOR_FEATURES_INFORMATION { // same size in both x86 and x64
   ULONGLONG ProcessorFeatureBits;                                            // 0x000 0x000
   ULONGLONG Reserved[3];                                                     // 0x008 0x008
} SYSTEM_PROCESSOR_FEATURES_INFORMATION, *PSYSTEM_PROCESSOR_FEATURES_INFORMATION;
```
