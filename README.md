1、Install the MiniMap plugin

https://www.unrealengine.com/marketplace/zh-CN/product/6895988c85964551a4a7dc8a18655642


2、Use plugins

Initialize the map plugin

![image](https://raw.githubusercontent.com/kx500/MiniMap/main/QQ%E6%88%AA%E5%9B%BE20221201133247.jpg)



Add Marker

![image](https://raw.githubusercontent.com/kx500/MiniMap/main/QQ%E6%88%AA%E5%9B%BE20221201133323.jpg)



bind the click event

![image](https://raw.githubusercontent.com/kx500/MiniMap/main/QQ%E6%88%AA%E5%9B%BE20221201133341.jpg)



Features:

Support pure blueprint and C++ calls

Freely add markers

Ultra high performance optimization with almost no efficiency impact

Small map shape (round or square) can be set

Parameter：
init(
FVector2D ContainerSize, //Small map container size
FVector2D WorldSize,     //Landscape size
FVector2D WorldPosition, // Landscape Location Offset in Editor
AActor* Player,          // self Player actor
UUserWidget*& Map,       // Return value. When initialization is completed, a control will be returned for insertion into the small map container
int Scale,               // Small map and world size ratio
float Zoom,              // The default scale is a floating point value of 0 - 1.
int UpdateDelay,         // Update speed of small map markers, in milliseconds
EMapType MapType         // Display mode of small map, rectangle or circle
);


中文说明：
https://blog.csdn.net/qq_39447679/article/details/125865075


