# SYSTEM_BOOT_GRAPHICS_INFORMATION

```C
typedef struct _SYSTEM_BOOT_GRAPHICS_INFORMATION { // same size in both x86 and x64
   LARGE_INTEGER       FrameBuffer;                                           // 0x000 0x000
   ULONG               Width;                                                 // 0x008 0x008
   ULONG               Height;                                                // 0x00c 0x00c
   ULONG               PixelStride;                                           // 0x010 0x010
   ULONG               Flags;                                                 // 0x014 0x014
   SYSTEM_PIXEL_FORMAT Format;                                                // 0x018 0x018
   ULONG               DisplayRotation;                                       // 0x01c 0x01c
} SYSTEM_BOOT_GRAPHICS_INFORMATION, *PSYSTEM_BOOT_GRAPHICS_INFORMATION;
```
