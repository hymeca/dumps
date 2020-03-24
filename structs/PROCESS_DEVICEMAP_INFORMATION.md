# PROCESS_DEVICEMAP_INFORMATION

```C
typedef struct _PROCESS_DEVICEMAP_INFORMATION { // x86 = 36, x64 = 40
   union {                                                         // 0x000 0x000
      struct {
         HANDLE DirectoryHandle;                                   // 0x000 0x000
      } Set;

      struct {
         ULONG DriveMap;                                           // 0x000 0x000
         UCHAR DriveType[32];                                      // 0x000 0x000
      } Query;
   };
} PROCESS_DEVICEMAP_INFORMATION, *PPROCESS_DEVICEMAP_INFORMATION;
```
