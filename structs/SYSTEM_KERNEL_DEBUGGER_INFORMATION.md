# SYSTEM_KERNEL_DEBUGGER_INFORMATION

```C
typedef struct _SYSTEM_KERNEL_DEBUGGER_INFORMATION { // same size in both x86 and x64
   BOOLEAN KernelDebuggerEnabled;                                               // 0x000 0x000
   BOOLEAN KernelDebuggerNotPresent;                                            // 0x001 0x001
} SYSTEM_KERNEL_DEBUGGER_INFORMATION, *PSYSTEM_KERNEL_DEBUGGER_INFORMATION;
```
