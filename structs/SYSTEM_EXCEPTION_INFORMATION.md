# SYSTEM_EXCEPTION_INFORMATION

```C
typedef struct _SYSTEM_EXCEPTION_INFORMATION { // same size in both x86 and x64
   ULONG AlignmentFixupCount;                                                 // 0x000 0x000
   ULONG ExceptionDispatchCount;                                              // 0x004 0x004
   ULONG FloatingEmulationCount;                                              // 0x008 0x008
   ULONG ByteWordEmulationCount;                                              // 0x00c 0x00c
} SYSTEM_EXCEPTION_INFORMATION, *PSYSTEM_EXCEPTION_INFORMATION;
```
