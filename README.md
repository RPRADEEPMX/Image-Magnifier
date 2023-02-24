# Image-Magnifier

### Description

This widget is used to view your image in zoom on mouse hover which means Magnify. The following steps helps to use this widget in your application.

### Dependencies
•	Studio pro version 9.19.0

### Configuration
•	Generalize your entity with System.Image.

•	Add a new String attribute to update the mendix image url as highlighted in below image.
![image](https://user-images.githubusercontent.com/126260956/221257243-f4daf0d5-a7d9-4627-9b74-9b42cdc5ea41.png)

 
•	Create a Nanoflow in your Mendix modular with following activities.
![image](https://user-images.githubusercontent.com/126260956/221257261-905dd463-104c-4e44-9af7-6e34712685c0.png)

 
•	Creating GUID for the image uploaded using Get GUID Java action.

•	Application url will be created automatically by using Get remote url activity.

•	Manually Configure your url value in change object activity as given below image.
![image](https://user-images.githubusercontent.com/126260956/221257352-4eaf5676-5532-49c2-913b-c264c9d45645.png)


•	Place the widget inside a data view which is configured with your entity that is generalized with System.Image entity.

•	Select the Image url attribute inside the widget as given in below image.
![image](https://user-images.githubusercontent.com/126260956/221257393-5724caf0-292b-4839-b93d-083a846e94d2.png)

 
### Result

•	As a result you can magnify your image on hover.

![image](https://user-images.githubusercontent.com/126260956/221257456-cb3a3450-3319-4300-b9fd-7394c8c9fb0c.png)
 

 
