

# Check drives in windows via terminal:

Command to run to only get the mounted drive names:
```
wmic logicaldisk get name
```
EXAMPLE OUTPUT:
```
Name
C:
D:
G:
```
Command to run to get to know the mounted drive name and their size:
```
wmic logicaldisk get name,size
```
EXAMPLE OUTPUT:
```
Name  Size
C:    255142653952
D:    2000396742656
G:    2000396742656
```
*Note:* The size is given in bytes.

Command in order to get the mounted drive names as well as the their size in GB:
```
powershell "get-psdrive -psprovider filesystem"
```
EXAMPLE OUTPUT:
```
Name           Used (GB)     Free (GB) Provider      Root
----           ---------     --------- --------      ----
C                 207.41         30.21 FileSystem    C:\
D                1018.37        844.64 FileSystem    D:\
G                1060.60        802.41 FileSystem    G:\
```
