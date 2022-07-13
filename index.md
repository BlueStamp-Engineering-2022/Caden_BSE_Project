Face Recognition Door Lock
A camera connected to a Raspberypi captures the user's face. It uploads the image to an API (Amazon Rekognition) which uses facial recognition to determine whether to open the lock. If the open response is sent back the arduino toggles a motor which opens the lock.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Caden Wei | Junipero Serra Highschool | Mechanical Engineering | Incoming Sophmore

![IMG_5549](https://user-images.githubusercontent.com/86168345/174658475-f27000dc-83d3-4028-bc24-160bf40c370a.JPG)

  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint.

[![Thumbnail2](https://user-images.githubusercontent.com/86168345/178777770-80836957-bef0-45f8-8927-e1482bdc6598.jpg)](https://www.youtube.com/watch?v=VKctLer_IKs&ab_channel=BlueStampEng)
  
![image](https://user-images.githubusercontent.com/86168345/175608678-4d140eff-fca2-440a-9540-0eb22442cb78.png)

My first milestone was being able to process images using Amazon's Rekognition API. This meant I had to set up my raspberry pi. I downloaded the OS on a SD card and set up the Pi on a monitor. I enabled SSH and grabbed the Pi's IP adress. I could then run the Raspi headless through the command prompt on my computer. Then I had the connect the Raspi to the API. I first set up an AWS (Amazon web services) account. I configured the CLI to be able to access my AWS console from my raspi which is being run headless on my laptop. I then had to give my Raspi custom permissions to access the account. I then needed to create a lambda function to link Alexa skills which allows my lock to interact with Alexa.

[![Thumbnail1](https://user-images.githubusercontent.com/86168345/174659342-bbe59611-2fd2-44f0-a97b-827f0d77fddb.jpg)
](https://www.youtube.com/watch?v=KoR6Z2y8akA&ab_channel=BlueStampEng)

# Starter Project

My starter project the useless machine was elegantly simple. It doesn't use any computing chips or controllers just logic from a simple circuit. The useless machine is a box with a conspicuous switch. When the switch is toggled an arm emerges from a door and closes the switch. The arm then returns. I first soldered the switch, terminals, lights, resisters, and a small pressure switch to a printed circuit board. I hooked the PCB to the motor and a battery pack. Then I constructed the box surrounding the internal components. When I first started I assumed there would need to a seperate mechanism to open the door but the arm itself pushes it open.

