# SYSTEM_ACPI_AUDIT_INFORMATION

```C
typedef struct _SYSTEM_ACPI_AUDIT_INFORMATION { // same size in both x86 and x64
   ULONG RsdpCount;                                                          // 0x000 0x000
   ULONG SameRsdt : 1;                                                       // 0x004 0x004
   ULONG SlicPresent : 1;                                                    // 0x004 0x004
   ULONG SlicDifferent : 1;                                                  // 0x004 0x004
} SYSTEM_ACPI_AUDIT_INFORMATION, *PSYSTEM_ACPI_AUDIT_INFORMATION;
```
