# PROCESS_DEVICEMAP_INFORMATION_EX

```C
// #definde PROCESS_LUID_DOSDEVICES_ONLY 0x00000001 /* Flags */

typedef struct _PROCESS_DEVICEMAP_INFORMATION_EX { // x86 = 40, x64 = 48
   union {                                                         // 0x000 0x000
      struct {
         HANDLE DirectoryHandle;                                   // 0x000 0x000
      } Set;

      struct {
         ULONG DriveMap;                                           // 0x000 0x000
         UCHAR DriveType[32];                                      // 0x000 0x000
      } Query;
   };
   ULONG Flags;                                                    // 0x024 0x028
} PROCESS_DEVICEMAP_INFORMATION_EX, *PPROCESS_DEVICEMAP_INFORMATION_EX;
```
