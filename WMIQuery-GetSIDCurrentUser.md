**Namespace:** root\cimv2

**Query:** SELECT SID FROM Win32_UserAccount WHERE Name = '*User Name*'

**Test:** Use WBEMTest.exe

**Test:** WMIC Path Win32_UserAccount WHERE "Name='%UserName%'" Get SID /value

**Test:** WMIC useraccount WHERE Name="%UserName%" Get SID /value

**Information**: [Win32_UserAccount class](https://docs.microsoft.com/en-us/windows/desktop/cimwin32prov/win32-useraccount)
