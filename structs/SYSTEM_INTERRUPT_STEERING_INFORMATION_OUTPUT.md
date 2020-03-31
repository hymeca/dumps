# SYSTEM_INTERRUPT_STEERING_INFORMATION_OUTPUT

```C
typedef struct _SYSTEM_INTERRUPT_STEERING_INFORMATION_OUTPUT { // same size in both x86 and x64
   ULONG Enabled : 1;                                                         // 0x000 0x000
   ULONG Reserved : 1;                                                        // 0x000 0x000
   ULONG AsULONG;                                                             // 0x000 0x000
} SYSTEM_INTERRUPT_STEERING_INFORMATION_OUTPUT, *PSYSTEM_INTERRUPT_STEERING_INFORMATION_OUTPUT;
```
