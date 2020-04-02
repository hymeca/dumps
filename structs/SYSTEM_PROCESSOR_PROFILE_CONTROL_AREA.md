# SYSTEM_PROCESSOR_PROFILE_CONTROL_AREA

```C
typedef struct _SYSTEM_PROCESSOR_PROFILE_CONTROL_AREA { // x86 = 8, x64 = 16
   PPROCESSOR_PROFILE_CONTROL_AREA ProcessorProfileControlArea;               // 0x000 0x000
   BOOLEAN                         Allocate;                                  // 0x004 0x008
} SYSTEM_PROCESSOR_PROFILE_CONTROL_AREA, *PSYSTEM_PROCESSOR_PROFILE_CONTROL_AREA;
```
