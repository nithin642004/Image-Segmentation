# Image Segmentation with U-Net

I used semantic image segmentation for this project. Here is an example of how semantic classification works, In the below figure the “Car” class is indicated below by the dark blue mask, and "Person" is indicated with a red mask:

<img src="images/carseg.png" style="width:500px;height:250;">
<caption><center> <u><b>Figure 1</u></b>: Example of a segmented image <br> </center></caption>


Key Take-overs:
* Building a U-Net model
* Training the model using Adam optimizer on the CARLA self-driving car data-set of 1000+ images
* Implementing semantic image segmentation on this
* Applying sparse categorical crossentropy for pixelwise prediction


Outputs using 40 epochs:

![image](https://user-images.githubusercontent.com/96827791/211162923-831e6194-57e1-47b9-9fc9-2946187c66a4.png)
![image](https://user-images.githubusercontent.com/96827791/211162960-bbef4556-2435-43a1-b583-f87138b11bd4.png)
![image](https://user-images.githubusercontent.com/96827791/211162962-d1830274-2709-4f2b-aba9-e9c4d7f7b62c.png)
![image](https://user-images.githubusercontent.com/96827791/211162968-6f1780fc-16af-499f-b7c7-319eba90cbff.png)

