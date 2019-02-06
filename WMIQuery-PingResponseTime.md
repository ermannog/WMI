**Namespace:** root\cimv2

**Query:** SELECT * FROM Win32_PingStatus WHERE Address = '*hostname or IP*'

**Test:** Use WBEMTest.exe

**Test:** WMIC Path Win32_PingStatus WHERE "Address='1270.0.1'" Get Responsetime /value

**Information**: [Win32_PingStatus class](https://docs.microsoft.com/en-us/previous-versions/windows/desktop/wmipicmp/win32-pingstatus)
