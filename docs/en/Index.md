## Network Model Management API
Edit
This documentation will cover the API description of the Network Model Management tools.
It will be seperated in different chapters which represents different modules of the solution:

### Identity Management
###### GET
- [Authorization](IdentityManagement/Authorization.md)

### File Management - Directory
###### GET
- [List all Directories](Filemanagement/ListAllDirectories.md)
- [Get Directory by ID](Filemanagement/GetDirectoryByID.md)
- [Get All Subdirectories](Filemanagement/GetAllSubdirectories.md)
###### DELETE
- [Delete Directory by ID](Filemanagement/DeleteDirectoryByID.md)
###### POST
- [Create new Folder](Filemanagement/CreateNewFolder.md)
- [Rename Folder](Filemanagement/RenameFolder.md)
- [Move Folder](Filemanagement/MoveFolder.md)

### File Management - File
###### GET
- List all Files in a directory
- Get a File by ID
- Get File content
- Download File by ID
###### DELETE
- Delete File by ID
###### POST
- Upload File ????
- Create a new File
- Move File to another folder
- Rename a File

### ODMS Function
###### GET
- [Get all Models](CIMModelManagement/ListAllModels.md)
- [Get A Model by ID](CIMModelManagement/GetModelByID.md)
###### DELETE
- [Delete Model by ID](CIMModelManagement/DeleteModelByID.md)
###### POST
- [Export an Incremental Model](CIMModelManagement/ExportIncrementalModel.md)
- [Export a Full Model](CIMModelManagement/ExportFullModel.md)