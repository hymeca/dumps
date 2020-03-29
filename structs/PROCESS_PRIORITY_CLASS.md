# PROCESS_PRIORITY_CLASS

```C
typedef struct _PROCESS_PRIORITY_CLASS { // same size in both x86 and x64
   BOOLEAN Foreground;                                                // 0x000 0x000
   UCHAR   PriorityClass;                                             // 0x001 0x001
} PROCESS_PRIORITY_CLASS, *PPROCESS_PRIORITY_CLASS;
```
