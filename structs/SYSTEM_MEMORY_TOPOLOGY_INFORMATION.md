# SYSTEM_MEMORY_TOPOLOGY_INFORMATION

```C
typedef struct _SYSTEM_MEMORY_TOPOLOGY_INFORMATION { // same size in both x86 and x64
   ULONGLONG            NumberOfRuns;                                           // 0x000 0x000
   ULONG                NumberOfNodes;                                          // 0x008 0x008
   ULONG                NumberOfChannels;                                       // 0x00c 0x00c
   PHYSICAL_CHANNEL_RUN Run[1];                                                 // 0x010 0x010
} SYSTEM_MEMORY_TOPOLOGY_INFORMATION, *PSYSTEM_MEMORY_TOPOLOGY_INFORMATION;
```
