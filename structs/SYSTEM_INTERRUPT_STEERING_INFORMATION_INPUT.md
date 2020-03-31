# SYSTEM_INTERRUPT_STEERING_INFORMATION_INPUT

```C
typedef struct _SYSTEM_INTERRUPT_STEERING_INFORMATION_INPUT { // x86 = 20, x64 = 24
   ULONG          Gsiv;                                                       // 0x000 0x000
   BOOLEAN        ControllerInterrupt;                                        // 0x004 0x004
   BOOLEAN        EdgeInterrupt;                                              // 0x005 0x005
   BOOLEAN        IsPrimaryInterrupt;                                         // 0x006 0x006
   GROUP_AFFINITY TargetAffinity;                                             // 0x008 0x008
} SYSTEM_INTERRUPT_STEERING_INFORMATION_INPUT, *PSYSTEM_INTERRUPT_STEERING_INFORMATION_INPUT;
```
