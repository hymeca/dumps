# BINDINFO_OPTIONS

```C
typedef enum {
   BINDINFO_OPTIONS_WININETFLAG = 0x10000,
   BINDINFO_OPTIONS_ENABLE_UTF8 = 0x20000,
   BINDINFO_OPTIONS_DISABLE_UTF8 = 0x40000,
   BINDINFO_OPTIONS_USE_IE_ENCODING = 0x80000,
   BINDINFO_OPTIONS_BINDTOOBJECT = 0x100000,
   BINDINFO_OPTIONS_SECURITYOPTOUT = 0x200000,
   BINDINFO_OPTIONS_IGNOREMIMETEXTPLAIN = 0x400000,
   BINDINFO_OPTIONS_USEBINDSTRINGCREDS = 0x800000,
   BINDINFO_OPTIONS_IGNOREHTTPHTTPSREDIRECTS = 0x1000000,
   BINDINFO_OPTIONS_IGNORE_SSLERRORS_ONCE = 0x2000000,
   BINDINFO_WPC_DOWNLOADBLOCKED = 0x8000000,
   BINDINFO_WPC_LOGGING_ENABLED = 0x10000000,
   BINDINFO_OPTIONS_ALLOWCONNECTDATA = 0x20000000,
   BINDINFO_OPTIONS_DISABLEAUTOREDIRECTS = 0x40000000,
   BINDINFO_OPTIONS_SHDOCVW_NAVIGATE = -2147483648
} BINDINFO_OPTIONS;
```