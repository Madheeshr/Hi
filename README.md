IBM WATSON IMAGE RECOGNITION

IBM Watson Visual Recognition is a tool that uses deep learning algorithms to analyze images and allow users to automatically identify subjects and objects contained within the image and organize and classify these images into categories. the interesting part is that it allows you to build your own custom image classifiers and then train and test those models in the cloud itself.

What you will learn from this?

You will utilize IBM Watson Visual Recognition (VR) to upload and classify your images using custom image classifiers built by you.

What you will require?

•	IBM Cloud account (A credit card is NOT required to sign up for IBM Cloud Lite account and there is no charge associated in creating a Lite plan instance of the Watson Discovery service).

•	Device with good internet connection.

You should see following dashboard after completing the guide till step 7 as mentioned in the prerequisites.
          For the custom model that we are creating in the visual recognition service, we are classifying 3 breeds of dogs. You can use any class of any objects like fruits, logos, different time of days like morning, afternoon, evening and night.

First Basic step we have to do is that we have to make a IBM Account on Link.
In this you just finish the verfication and all stuff that is required.
Then go to IBM dashboard but let me know that you are only have permission of making one Watson Assistant not two or three.

When you click on IBM Cloud you can see the dashboard there. And just as

1.Image recognition, also known as computer vision, is a field of artificial intelligence that involves teaching machines to interpret and understand visual information in the form of images or videos. This technology enables computers to identify and classify objects, scenes, and patterns within images, making it a valuable tool in a wide range of applications, from autonomous vehicles and medical diagnostics to content moderation and augmented reality

2.In the navigation bar i.e three lines in the left of the dashboard page, click on that and then click on RESOURCES LIST. Here you can see the list of resoureces you have used and those you haven't use yet. We are gonna make a service name Watson Assistant. SO how will you approach that. After clicking on Create Resourecs you will see a page like

Just Click on Watson Assistant and you will see a create page.

In this there are a lot of text inputs like region, plan, watson etc. I prefer to choose

Region - London if you are from the country in the given list then choose that.

Plan - LITE if you haven't a subscription of IBM.

Service Name - You have write watson-assistant-__ then you can write either of a number or alphabet like c9, 5n etc.

 And in this page you just choose the plan and leave all in their default positions.Click on Create. Okay we are going to launch Watson Assistant and make sure you are with me on this page : And one more thing here is, if you want to use this watson assistant in outside code so there you can see the API key and URL of this just copy and paste wherever you want to use this assistant. This is a great opporunity which watson offer. Here you can see two buttons :  
 
 *Launch Watson Assistant
 
Procedure 

1. Start by creating our first class for training. click on create a class tab.
    on next screen enter the name for your class. Let’s start with Husky, so we name our first class Husky.
   
2. Upload training dataset.     click on Browse, and select the dataset file (.zip file) which contains the training images for your class. i have chosen husky.
   
3. Add the uploaded dataset to your model.  click on the checkbox next to Husky.zip (in my case) and then click on Add to Model.

4. Now do the same with the dataset for Beagle and Golden Retriever. Then click “Train Model”.
 
5. Test your model.

•	click on the Test option, then browse to upload your test dataset (my test data contain mixture of all 3 types of dog breeds).
•	once you upload your test data, it will automatically start analyzing all images.
