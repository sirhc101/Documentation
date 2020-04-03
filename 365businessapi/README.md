# 365 business API
The `365 business API` app is the base library for all `365 business development` app, based on the `365 business API` services. The app is the base libary app to provide API communication capabilities. 

## Interfaces
The `365 business API` app is created as base library to communicate with the `365 business API` services. Therfor the app provides public interfaces to use for handling and consuming API services.

### 365 business API (Codeunit `5523562` - `bdev.365 business API`)
The `bdev.365 business API` codeunit object is the base component in consuming `365 business API` services and providing the base communication.

#### Methods
The following methods are available:

| Method name | Description | 
| --- | ---| 
| [CallApi(Text)](./365businessapi/CallApi1.md) | Sending a GET request to the API service. |
| [CallApi(Text, Text)](./365businessapi/CallApi2.md) | Sending a POST request to the API service. |
| [CallApi(Enum, Text, Text)](./365businessapi/CallApi3.md) | Sending a request to the API service. |
| [CallApi(Enum, Text, Text[10], Text)](./365businessapi/CallApi4.md) | Sending a request to a specific API service version. |
| [GetResponse(Record)](./365businessapi/GetResponse1.md) | Returns the content of the API Response. |
| [GetResponse(JsonObject)](./365businessapi/GetResponse2.md) | Returns the content of the API Response as JSON Object. |
| [IsSuccessful()](./365businessapi/IsSuccessful.md) | Checks whether be the previous API call successful or not. | 
| [GetException(Dictionary of [Text, Text])](./365businessapi/GetException.md) | Returns the exception caused by previous API call. |
| [GetExceptionMessage()](./365businessapi/GetExceptionMessage.md) | Returns the exception message caused by previous API call. |
| [GetExceptionStatus()](./365businessapi/GetExceptionStatus.md) | Returns the exception status caused by previous API call. | 
| [GetApiVersion()](./365businessapi/GetApiVersion1.md) | Returns the currently used API Version. | 
| [GetApiVersion(Code)](./365businessapi/GetApiVersion2.md) | Returns the API Version a specific service. | 
| [GetMajorApiVersion()](./365businessapi/GetMajorApiVersion1.md) | Returns the major version no. of the currently used API Version. | 
| [GetMajorApiVersion(Code)](./365businessapi/GetMajorApiVersion2.md) | Returns the major version no. of a specific service API Version. | 
| [GetMinorApiVersion()](./365businessapi/GetMinorApiVersion1.md) | Returns the minor version no. of the currently used API Version. | 
| [GetMinorApiVersion(Code)](./365businessapi/GetMinorApiVersion2.md) | Returns the minor version no. of a specific service API Version. | 
| [GetBuildApiVersion()](./365businessapi/GetBuildApiVersion1.md) | Returns the build version no. of the currently used API Version. | 
| [GetBuildApiVersion(Code)](./365businessapi/GetBuildApiVersion2.md) | Returns the build version no. of a specific service API Version. | 
| [GetRevisionApiVersion()](./365businessapi/GetRevisionApiVersion1.md) | Returns the revision version no. of the currently used API Version. | 
| [GetRevisionApiVersion(Code)](./365businessapi/GetRevisionApiVersion2.md) | Returns the revision version no. of the currently used API Version. | 
| [SetApiVersion(Code, Text)](./365businessapi/SetApiVersion.md) | Set the API Service Version to use in case of specific version used. |

### Data Type Management (Codeunit `5523565` - `bdev.API DataType Mgmt.`)

#### Methods
The following methods are available:

| Method name | Description | 
| --- | ---| 
| [GetInStreamFromBlobStorage(Codeunit, InStream)](./datatypemgmt/GetInStreamFromBlobStorage.md) | Initiate InStream object from Temp Blob codeunit to read data. |
| [GetOutStreamFromBlobStorage(Codeunit, OutStream)](./datatypemgmt/GetOutStreamFromBlobStorage.md) | Initiate OutStream object from Temp Blob codeunit to write data. |
| [GetTextFromBlobStorage(Codeunit)](./datatypemgmt/GetTextFromBlobStorage.md) | Read content from Temp Blob Codeunit and return Text object. |
| [SetTextToBlobStorage(Codeunit, Text)](./datatypemgmt/SetTextToBlobStorage.md) | Write a text to Temp Blob Codeunit. |
| [GetBase64Content(JsonObject, Text, Text, Text)](./datatypemgmt/GetBase64Content1.md) | Get base64 content of an API Response. |  
| [GetBase64Content(JsonObject, Text, Enum, Text)](./datatypemgmt/GetBase64Content2.md) | Get base64 content of an API Response. | 
| [TestJsonToken(JsonObject, Text)](./datatypemgmt/TestJsonToken.md) | Test whether the specified JSON token exists or not. | 
| [GetJsonToken(JsonObject, Text)](./datatypemgmt/GetJsonToken.md) | Retrieves the specified JSON token by given key name. |
| [SelectJsonToken(JsonObject, Text)](./datatypemgmt/SelectJsonToken.md) | Retrieves the specified JSON token by given path. |
| [ConcatenateText(Text, Text)](./datatypemgmt/ConcatenateText1.md) | Concatenate text with whitespace in between. |
| [ConcatenateText(Text, Text, Text)](./datatypemgmt/ConcatenateText2.md) | Concatenate text with specific merge text in between. |

### Exception (Codeunit `5523566` - `bdev.API Exception`)

#### Methods
The following methods are available:

| Method name | Description | 
| --- | ---| 
