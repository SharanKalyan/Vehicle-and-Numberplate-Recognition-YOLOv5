# Numberplate-Recognition-YOLOv5

Collected ~5000 images of Vehicles that are commonly seen across India and UAE, annotated the different types of vehicles (to identify the vehicle type) and their Numberplates using annotation tools such as LabelIMG.
Trained the YOLOv5L on those 5000 images and this public repo consists of the samples of the data on which I tested the model's performance.

### The main goal is to automate vehicle access within a community.
When a vehicle arrives at the entrance, the system captures an image of it. A model then identifies the vehicle type and detects its license plate. The license plate area is extracted, and OCR tools such as PyTesseract are used to read the text on the plate. Once the text is retrieved, it is compared against a database containing all authorized license plates to determine whether the vehicle is allowed to enter.

The results are tested on Indian conditions where the number plates might not all be the same. We have lots of inconsistencies, yet the model was able to extract the liscense plates and the type of vehicle. 
On foreign conditions, the model performed much better! 

We can also compress the NMS to a minimum threshold and therby reducing the clutter during the runtime! 

## You can find more images / Outputs in the "Results" Directory

# **Foreign Roads - Abu Dhabi**

![abudhabi](https://github.com/user-attachments/assets/e31a5464-d642-4fc9-9703-08f83d9d6abd)

![AbudhabiCorniche](https://github.com/user-attachments/assets/115f7277-d56b-449b-9433-74bc84088f50)

# **Indian Roads**

![Streets_Of_Chennai](https://user-images.githubusercontent.com/20862520/189132881-163fc0a8-0901-45fb-ab31-11b38538be57.gif)


![share](https://user-images.githubusercontent.com/20862520/149266907-0d5cc005-4ee5-4103-b003-91c6fd01db02.jpg)

In the below image, you can see that the model was able to identify the type of vehicle as well as the Numberplate on Indian Conditions.
![red](https://user-images.githubusercontent.com/20862520/147906666-4aa7f3c0-abc7-4bde-a773-404685f390f7.jpg)

The licenceplate was identified and the text is extracted out of the image

![red](https://user-images.githubusercontent.com/20862520/147911514-262d3cca-8f0c-4a6e-981b-344904a2739b.jpg)       -->     MH14DX5842














