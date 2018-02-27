**Namespace:** root\cimv2

**Query:** SELECT * FROM Win32_OperatingSystem WHERE Version LIKE '10.%' and ProductType='1'

**Test:** Use WBEMTest.exe

**Information**:

From [Win32_OperatingSystem class](https://msdn.microsoft.com/en-us/library/aa394239(v=vs.85).aspx):

```
***ProductType:*** *Additional system information*
* *Work Station = 1*
* *Domain Controller = 2*
* *Server = 3*

**Version:*** *Version number of the operating system*
```
