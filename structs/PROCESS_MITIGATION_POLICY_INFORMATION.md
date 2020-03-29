# PROCESS_MITIGATION_POLICY_INFORMATION

```C
typedef struct _PROCESS_MITIGATION_POLICY_INFORMATION { // same size in both x86 and x64
   PROCESS_MITIGATION_POLICY Policy;                                                 // 0x000 0x000
   union {
      PROCESS_MITIGATION_ASLR_POLICY ASLRPolicy;                                     // 0x004 0x004
      PROCESS_MITIGATION_STRICT_HANDLE_CHECK_POLICY StrictHandleCheckPolicy;         // 0x004 0x004
      PROCESS_MITIGATION_SYSTEM_CALL_DISABLE_POLICY SystemCallDisablePolicy;         // 0x004 0x004
      PROCESS_MITIGATION_EXTENSION_POINT_DISABLE_POLICY ExtensionPointDisablePolicy; // 0x004 0x004
      PROCESS_MITIGATION_DYNAMIC_CODE_POLICY DynamicCodePolicy;                      // 0x004 0x004
      PROCESS_MITIGATION_CONTROL_FLOW_GUARD_POLICY ControlFlowGuardPolicy;           // 0x004 0x004
      PROCESS_MITIGATION_BINARY_SIGNATURE_POLICY SignaturePolicy;                    // 0x004 0x004
      PROCESS_MITIGATION_FONT_DISABLE_POLICY FontDisablePolicy;                      // 0x004 0x004
      PROCESS_MITIGATION_IMAGE_LOAD_POLICY ImageLoadPolicy;                          // 0x004 0x004
      PROCESS_MITIGATION_SYSTEM_CALL_FILTER_POLICY SystemCallFilterPolicy;           // 0x004 0x004
      PROCESS_MITIGATION_PAYLOAD_RESTRICTION_POLICY PayloadRestrictionPolicy;        // 0x004 0x004
      PROCESS_MITIGATION_CHILD_PROCESS_POLICY ChildProcessPolicy;                    // 0x004 0x004
      PROCESS_MITIGATION_SIDE_CHANNEL_ISOLATION_POLICY SideChannelIsolationPolicy;   // 0x004 0x004
   } DUMMYUNIONNAME;
} PROCESS_MITIGATION_POLICY_INFORMATION, *PPROCESS_MITIGATION_POLICY_INFORMATION;
```
