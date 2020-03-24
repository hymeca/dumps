# PROCESS_EXTENDED_ENERGY_VALUES

```C
typedef struct _PROCESS_EXTENDED_ENERGY_VALUES { // same size in both x86 and x64
   PROCESS_ENERGY_VALUES           Base;                                           // 0x000 0x000
   PROCESS_ENERGY_VALUES_EXTENSION Extension;                                      // 0x110 0x110
} PROCESS_EXTENDED_ENERGY_VALUES, *PPROCESS_EXTENDED_ENERGY_VALUES;
```
