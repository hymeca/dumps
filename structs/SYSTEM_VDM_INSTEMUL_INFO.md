# SYSTEM_VDM_INSTEMUL_INFO

```C
typedef struct _SYSTEM_VDM_INSTEMUL_INFO { // same size in both x86 and x64
   ULONG SegmentNotPresent;                                                   // 0x000 0x000
   ULONG VdmOpcode0F;                                                         // 0x004 0x004
   ULONG OpcodeESPrefix;                                                      // 0x008 0x008
   ULONG OpcodeCSPrefix;                                                      // 0x00c 0x00c
   ULONG OpcodeSSPrefix;                                                      // 0x010 0x010
   ULONG OpcodeDSPrefix;                                                      // 0x014 0x014
   ULONG OpcodeFSPrefix;                                                      // 0x018 0x018
   ULONG OpcodeGSPrefix;                                                      // 0x01c 0x01c
   ULONG OpcodeOPER32Prefix;                                                  // 0x020 0x020
   ULONG OpcodeADDR32Prefix;                                                  // 0x024 0x024
   ULONG OpcodeINSB;                                                          // 0x028 0x028
   ULONG OpcodeINSW;                                                          // 0x02c 0x02c
   ULONG OpcodeOUTSB;                                                         // 0x030 0x030
   ULONG OpcodeOUTSW;                                                         // 0x034 0x034
   ULONG OpcodePUSHF;                                                         // 0x038 0x038
   ULONG OpcodePOPF;                                                          // 0x03c 0x03c
   ULONG OpcodeINTnn;                                                         // 0x040 0x040
   ULONG OpcodeINTO;                                                          // 0x044 0x044
   ULONG OpcodeIRET;                                                          // 0x048 0x048
   ULONG OpcodeINBimm;                                                        // 0x04c 0x04c
   ULONG OpcodeINWimm;                                                        // 0x050 0x050
   ULONG OpcodeOUTBimm;                                                       // 0x054 0x054
   ULONG OpcodeOUTWimm;                                                       // 0x058 0x058
   ULONG OpcodeINB;                                                           // 0x05c 0x05c
   ULONG OpcodeINW;                                                           // 0x060 0x060
   ULONG OpcodeOUTB;                                                          // 0x064 0x064
   ULONG OpcodeOUTW;                                                          // 0x068 0x068
   ULONG OpcodeLOCKPrefix;                                                    // 0x06c 0x06c
   ULONG OpcodeREPNEPrefix;                                                   // 0x070 0x070
   ULONG OpcodeREPPrefix;                                                     // 0x074 0x074
   ULONG OpcodeHLT;                                                           // 0x078 0x078
   ULONG OpcodeCLI;                                                           // 0x07c 0x07c
   ULONG OpcodeSTI;                                                           // 0x080 0x080
   ULONG BopCount;                                                            // 0x084 0x084
} SYSTEM_VDM_INSTEMUL_INFO, *PSYSTEM_VDM_INSTEMUL_INFO;
```
