# Workflow

## 1) Acquire X-Ray

![image](/pbar.png)

Proceed to this step once you have set up the G4 system and obtained an intial x-ray in the form of an .xrf file. 

1. First, navigate to the X-Ray database and find the X-Ray files using the browse button. Use this to browse the database of X-Rays to judge whether the X-Rays are usable. If so, copy the directory path from the top right box and paste it into the "Input Current Directory" field in the Load New X-Ray tab. <b> This will only import the most RECENTLY created X-Ray. </b> Then click "Get Latest X-Ray".  (See Video Below For Illustration) 

2. <b> Adjust the contrast and sharpening levels</b>. The sharpening feature highlights fine detail on the X-Ray and is achieved through spatial differentiation of pixels in the image.

3. Once skull in X-Ray looks easily identifiable, click the "Import To Planning" button to move on.

<p align = "center">
<img src=import.gif> 
</p>

## 2) Set Skull Dimensions

![image](/pbar2.png)

<br> 
1. The first step in this task is to <b> adjust the larger, orange ellipse to fit the mouse's skull </b> as seen in the video.

<blockquote> The <b> inner, white ellipse </b> is an estimation of the <b> mouses brain </b>. Fit accordingly by this standard. This was obtained through a CT segmented imaged of a 28g nude normal male mouse from the Digimouse project (Biomedical Imaging Group - University of Southern California). </blockquote>
<blockquote> The <b> larger, orange ellipse </b> is an estimation of the mouse's skull relative to the inner white ellipse. </blockquote>

2. Once the ellipses are properly placed, four points are available for targeting: Superior Right, Inferior Right, Superior Left and Inferior Left. Their labels can be illustrated on the targeting screen by clicking <b> Show Target Description </b>. These points are the centroid values for each section of the brain. 

3. Use the <b> Select Target </b> button to choose the target location. After confirming a target you'll be able to change the target to any one of the 35 positions available and still keep track of the planned target"

4. Use the <b> Show Possible Positions </b> button to ensure your chosen location falls into the possible area of targeting indicated by the area of white dots. 

<blockquote> The white dots show the possible 35 targets that the software can direct the ultrasound towards. Your chosen quadrant must fall within this area. If it doesn't, <b> you will have to reposition the mouse and retake the X-Ray </b> </blockquote>

<p align = "center">
<img src=targeting.gif> 
</p>


## 3) Confirm Target Location To Select Correct Base
![image](/pbar3.png)

1. Take a look at the X-Ray with the planned and calculated targets and decide if that is the location you would like to send the focused ultrasound energy. If that is not the location you wish, use the sliders to move in the head-tail and right-left direction. Observe that as you change the location a new base number and arrow direction is shown on the <b> purple box. </b> ([What are the bases?](uPET.md))

<blockquote> The <b> purple dot </b> is the calculated target, and is the target based on the ellipse target you aligned back in step 2. If you believe there is a better location, you can directly change the target with the sliders without having to go back to realign the ellipse. </blockquote>

<blockquote> The <b> blue circle</b> is used to provide a reference similar to the original ellipse.  </blockquote>

2. Once the final target is decided your task is to get the correct base given to you by the software's purple box. Take note of this number and retrive the correct base from the transducer bases box and place in the uPET-FUS bed. You might want to <b> Show input for motion detection </b> to confirm the mouse's head is properly segmented. 

3. After placing the mouse in the G4 with the right base go back to Genesys so you can acquire the new X-Ray in the final step


## 4) Re-acquire X-Ray To Verify

![image](/pbar4.png)

1. Re-acquire X-Ray to verify mouse did not move during Transducer Placement. Follow the X-Ray acquisition guide to obtain the confirmation X-Ray and make sure you have saved it on your main directory folder. 

2. Once you acquired the X-Ray press <b> Load X-Ray with Transducer </b> on the Therapy tab.  Adjust the contrast level. 

3. Observe if the mouse has moved using the software's built in algorithim. If the box is <b> red </b> (very unlikley to happen), a significant movement happened and you need to go back to step one.

4. If the mouse hasn't moved, you can start handling the power equipment to turn on the transducer