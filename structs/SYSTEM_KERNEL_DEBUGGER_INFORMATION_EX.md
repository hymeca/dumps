# SYSTEM_KERNEL_DEBUGGER_INFORMATION_EX

```C
typedef struct _SYSTEM_KERNEL_DEBUGGER_INFORMATION_EX { // same size in both x86 and x64
   BOOLEAN DebuggerAllowed;                                                     // 0x000 0x000
   BOOLEAN DebuggerEnabled;                                                     // 0x001 0x001
   BOOLEAN DebuggerPresent;                                                     // 0x002 0x002
} SYSTEM_KERNEL_DEBUGGER_INFORMATION_EX, *PSYSTEM_KERNEL_DEBUGGER_INFORMATION_EX;
```
