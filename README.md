Download Link: https://assignmentchef.com/product/solved-mtrn4230-assignment-2
<br>
The following assessment aims are derived from course learning outcome 4:

<ol>

 <li>Knowledge of basic image processing techniques for robotics.</li>

 <li>Demonstrate the ability to combine basic image processing techniques to achieve a given outcome.</li>

</ol>

<h1>INSTRUCTIONS</h1>

<ol>

 <li>Download all images relevant to this assignment from course resources.</li>

 <li>Assignment submission should consist of two files:

  <ol>

   <li>A report (in <strong>.pdf format</strong>) describing your step by step approach for each problem, answers, and corresponding image results,</li>

   <li>A single Matlab script which contains all necessary code used for the assignment.</li>

  </ol></li>

 <li>Develop your Matlab script in the same folder as the images and avoid using absolute paths (i.e.: Always use <strong>imread(‘image.jpg’)</strong> instead of <strong>imread(‘C:/absolute/path/image.jpg’)</strong>). This allows tutors to check your code efficiently.</li>

</ol>

<h1>ACTIVITIES</h1>

<ol>

 <li>Part 1: Complete the following tasks using ‘toysflash.png’:

  <ol>

   <li>Use a Matlab function to find the height, width, and number of channels of the image.</li>

  </ol></li>

</ol>

(1 point)

<ol>

 <li>Write a code to generate a binary mask which covers the blue cup in the image. Display this binary mask in a separate image. You can use Matlab’s <strong>Color Thresholder</strong> tool <strong>ONLY</strong> for the purpose of identifying the suitable color threshold values. You must write your own code to generate the final image. (2 point)</li>

 <li>Similarly create a binary mask covering the plastic ball at the front of the image.</li>

</ol>

Display this binary mask in a separate image. (1 point)

<ol>

 <li>Generate a colour mask containing both objects in (b) and (c) as shown in Fig. 1. Briefly describe how you achieved this goal. (1 point)</li>

</ol>







<em>Figure 1 Colour mask for the cup and the plastic ball. </em>

<ol start="2">

 <li>Part-2: Complete the following tasks using ‘chess_knights_run.png’ and ‘knight.png’:

  <ol>

   <li>Plot all SURF descriptors overlaid on ‘chess_knights_run.png’. (1 points)</li>

   <li>Match SURF descriptors from ‘knight.png’ to ‘chess_knights_run.png’. Visualise the matched pairs. (3 point)</li>

   <li>Using these two images and the feature matching concept, write an algorithm to find the distance between the two white knights on the chess board. The algorithm should work on any image where both white knights are on dark squares. Any answer within +/- 30 pixels from the true distance is accepted. In the report, describe how you solved this problem with corresponding images results. (3 points)</li>

  </ol></li>

</ol>




<ol start="3">

 <li>Part 3: Complete the following tasks using ‘oranges.jpg’ image: (8 points)

  <ol>

   <li>Write a code to identify the centres of each orange slice. Display markers on the centre of each orange slice. For full marks, you should identify at least 12 centres with no more than 2 incorrect centres. In the report, briefly write down the steps you followed to achieve this task with corresponding image outputs. (3 point)</li>

   <li>Detect the boundaries of the orange slices. Display the boundaries overlaid on the original image. Figure 2 shows answers accepted as a correct boundary. A boundary is considered correct, if the boundary covers at least 80% of the visible boundary of a slice. For full marks, boundaries corresponding to at least 11 slices should be identified with no more than 7 incorrect boundary lines. See Figure 3 for an example solution.  Briefly write down the steps you followed to achieve this task along with corresponding images.  (3 points)</li>

  </ol></li>

</ol>







<em>Figure 2: Any result closer to the edge (in green) of the slice is considered correct. To be accepted as a correct boundary, at least 80% of the visible border should be identified. </em>




<em>Figure 3: A sample solution. Incorrect boundary lines are circled. Question marks show missing boundary lines. </em>




<ol>

 <li>Create a binary mask for the seven slices on the top layer (The seven slices are marked in Figure 4). For full marks, masks for at least 5 slices should be displayed with no more than one incorrect mask. Masks should fully cover the slice. Describe your approach briefly along with corresponding images. (2 points)</li>

</ol>







<em>Figure 4: The seven slices on the top layer. </em>