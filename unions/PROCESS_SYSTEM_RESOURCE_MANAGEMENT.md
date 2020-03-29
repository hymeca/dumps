# PROCESS_SYSTEM_RESOURCE_MANAGEMENT

```C
typedef union _PROCESS_SYSTEM_RESOURCE_MANAGEMENT { // same size in both x86 and x64
   ULONG    Flags;                                                            // 0x000 0x000
   struct {
      ULONG Foreground : 1;                                                   // 0x000 0x000
      ULONG Reserved : 31;                                                    // 0x000 0x000
   };
} PROCESS_SYSTEM_RESOURCE_MANAGEMENT, *PPROCESS_SYSTEM_RESOURCE_MANAGEMENT;
```
