# RTL_CALLER_ALLOCATED_ACTIVATION_CONTEXT_STACK_FRAME_BASIC

```C
typedef struct _RTL_CALLER_ALLOCATED_ACTIVATION_CONTEXT_STACK_FRAME_BASIC { // x86 = 20, x64 = 40
   SIZE_T                             Size;                                           // 0x000 0x000
   ULONG                              Format;                                         // 0x004 0x008
   RTL_ACTIVATION_CONTEXT_STACK_FRAME Frame;                                          // 0x008 0x010
} RTL_CALLER_ALLOCATED_ACTIVATION_CONTEXT_STACK_FRAME_BASIC,
*PRTL_CALLER_ALLOCATED_ACTIVATION_CONTEXT_STACK_FRAME_BASIC;
```
