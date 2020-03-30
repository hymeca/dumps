# OLETLSFLAGS

```C
typedef enum {
   OLETLS_LOCALTID = 1,
   OLETLS_UUIDINITIALIZED = 2,
   OLETLS_INTHREADDETACH = 4,
   OLETLS_CHANNELTHREADINITIALZED = 8,
   OLETLS_WOWTHREAD = 16,
   OLETLS_THREADUNINITIALIZING = 32,
   OLETLS_DISABLE_OLE1DDE = 64,
   OLETLS_APARTMENTTHREADED = 128,
   OLETLS_MULTITHREADED = 256,
   OLETLS_IMPERSONATING = 512,
   OLETLS_DISABLE_EVENTLOGGER = 1024,
   OLETLS_INNEUTRALAPT = 2048,
   OLETLS_DISPATCHTHREAD = 4096,
   OLETLS_HOSTTHREAD = 8192,
   OLETLS_ALLOWCOINIT = 16384,
   OLETLS_PENDINGUNINIT = 0x8000,
   OLETLS_FIRSTMTAINIT = 0x10000,
   OLETLS_FIRSTNTAINIT = 0x20000,
   OLETLS_APTINITIALIZING = 0x40000,
   OLETLS_UIMSGSINMODALLOOP = 0x80000,
   OLETLS_MARSHALING_ERROR_OBJECT = 0x100000,
   OLETLS_WINRT_INITIALIZE = 0x200000,
   OLETLS_APPLICATION_STA = 0x400000,
   OLETLS_IN_SHUTDOWN_CALLBACKS = 0x800000,
   OLETLS_POINTER_INPUT_BLOCKED = 0x1000000,
   OLETLS_IN_ACTIVATION_FILTER = 0x2000000,
   OLETLS_ASTATOASTAEXEMPT_QUIRK = 0x4000000,
   OLETLS_ASTATOASTAEXEMPT_PROXY = 0x8000000,
   OLETLS_ASTATOASTAEXEMPT_INDOUBT = 0x10000000,
   OLETLS_DETECTED_USER_INITIALIZED = 0x20000000,
   OLETLS_BRIDGE_STA = 0x40000000,
   OLETLS_NAINITIALIZING = -2147483648
} OLETLSFLAGS;
```