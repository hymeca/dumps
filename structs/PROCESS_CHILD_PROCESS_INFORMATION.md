# PROCESS_CHILD_PROCESS_INFORMATION

```C
typedef struct _PROCESS_CHILD_PROCESS_INFORMATION { // same size in both x86 and x64
   BOOLEAN ProhibitChildProcesses;                         // 0x000 0x000
   BOOLEAN AlwaysAllowSecureChildProcess;                  // 0x001 0x001
   BOOLEAN AuditProhibitChildProcesses;                    // 0x002 0x002
} PROCESS_CHILD_PROCESS_INFORMATION, *PPROCESS_CHILD_PROCESS_INFORMATION;
```
