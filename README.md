# ANPR-vehicle-entry-exit-management-system-with-YOLOv5

### Objective: To develop a system for Supervision of Vehicle Entry-Exit into a premises <br>
![image](https://user-images.githubusercontent.com/58140667/205455077-55c6edf3-9e38-4383-8e7d-6d72d0ff7284.png)
<br>

The Basic Workflow of the Application is
1. Object Detection.
2. Image processing on the detected object (Number Plate).
3. Text Extraction using OCR
4. Storing and match the result from MySQL database

<h1> Object detection </h1>
Object detection is an application of computer vision and image processing that deals with detecting instances of
semantic objects of a certain class (such as humans, buildings, cars or anything that can be visually distinguished) in
digital images and videos.
It refers to the process of discovering the location of objects in images. To do this, computer vision algorithms must
first be able to recognize objects. Object recognition is a foundational subfield within computer vision that allows
the software to identify specific features based on their visual attributes, such as proportion, position, and appearance.
Once objects have been identified, object detection can find and localize these targets in images. 
<br>
<br>

Below is the screenshot of the programme 
<br>
![2](https://user-images.githubusercontent.com/58140667/192157053-b5187cd2-8e53-486f-b84b-3e7a9f2dc0f9.PNG)

<br>
<br>

<h2> Labeling specification for object detection </h2>
class_id: Object class name in nominal value (example 0,1,2) <br>
x_center : X component of center of bounding box <br>
y_center : Y component of center of bounding box <br>
width    : width of bounding box <br>
Height   : height of bounding box <br>

We used LabelImg repo as it provide a graphical image annotation tool  <br>
Repo: https://github.com/heartexlabs/labelImg <br>
