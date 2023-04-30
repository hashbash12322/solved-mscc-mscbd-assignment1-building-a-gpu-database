Download Link: https://assignmentchef.com/product/solved-mscc-_mscbd-assignment1-building-a-gpu-database
<br>



<h1>1           Assignment Information</h1>

<table width="371">

 <tbody>

  <tr>

   <td width="156">Course:</td>

   <td width="215">MSCC / MSCBD</td>

  </tr>

  <tr>

   <td width="156">Stage / Year:</td>

   <td width="215">1</td>

  </tr>

  <tr>

   <td width="156">Module:</td>

   <td width="215">Cloud Platforms &amp; Applications</td>

  </tr>

  <tr>

   <td width="156">Semester:</td>

   <td width="215">1</td>

  </tr>

  <tr>

   <td width="156">Assignment:</td>

   <td width="215">1 of 3</td>

  </tr>

  <tr>

   <td width="156">Date of Issue:</td>

   <td width="215">2021-03-04</td>

  </tr>

  <tr>

   <td width="156">Assignment Deadline:</td>

   <td width="215">2021-04-18 @ 23:55 (End of week ??)</td>

  </tr>

  <tr>

   <td width="156">Assignment Submission:</td>

   <td width="215">Upload to Moodle</td>

  </tr>

  <tr>

   <td width="156">Assignment Weighting:</td>

   <td width="215">10% of Module</td>

  </tr>

 </tbody>

</table>

<h1>2           Introduction</h1>

<strong>NOTE: read the whole assignment brief first before implementing it contains very important information</strong>

In this assignment you will be tasked with building an interactive database about GPUs (Graphics Processing Units) and the features they support. You will be expected to use a NoSQL type database as storage for this system. Your application must be capable of the following

<ul>

 <li>Add in a GPU with a series of features.</li>

 <li>Edit a currently existing GPU and its features.</li>

 <li>Be able to choose a set of supporting features and figure out which GPUs support them.</li>

</ul>

Your application will be similar to the format found at <a href="http://vulkan.gpuinfo.org/listreports.php">http://vulkan. </a><a href="http://vulkan.gpuinfo.org/listreports.php">gpuinfo.org/listreports.php</a>

If you click on any of the GPUs listed here it will bring you to another page. The information we are interested in here is listed under the “features” tab. You are required to map six features of a GPU which are the following: geometryShader, tesselationShader, shaderInt16, sparseBinding, textureCompressionETC2, and vertexPipelineStoresAndAtomics. Each GPU stored should contain the information for these six properties.

When a GPU is added a user should be able to click a series of checkboxes (or similar) to enable or disable features. When an add button is clicked there should be no duplicate names in the database or preexisting objects in the database for that GPU.

The score for your application will depend on:

<ol>

 <li>How fully featured, complete, and robust your code is. Along with howwell your UI is thought out (80%)</li>

 <li>How well documented is your code</li>

</ol>

<h1>5           Coding Brackets</h1>

<ol>

 <li>Bracket 1

  <ul>

   <li>Get the shell of the application with login/logout working</li>

   <li>Generate a model that will store the information of a GPU: name, manufacturer, date issued.</li>

   <li>Add the six properties listed in the introduction to the model of a GPU.</li>

   <li>the GPU name should be the key for each GPU in the database.</li>

  </ul></li>

 <li>Bracket 2

  <ul>

   <li>Build a UI form that will enable the user to add a GPU and all its information.</li>

   <li>When the form is submitted the GPU should be added to the database.</li>

  </ul></li>

 <li>Bracket 3  Prevent the overwriting of an object that is already in the database. <strong>Bracket Failure if object overwritten</strong>

  <ul>

   <li>Display a list of GPUs that are currently in the database by name only.</li>

  </ul></li>

 <li>Bracket 4

  <ul>

   <li>Make the GPU name list a set of hyperlinks.</li>

   <li>When a GPU name is clicked it should go to a seperate page showing the information and features for that GPU <strong>Bracket Failure if not on a seperate page</strong></li>

  </ul></li>

 <li>Bracket 5

  <ul>

   <li>Enable editing of a GPU in the database. The form or editing a GPU should be prepopulated with the existing information of the GPU in the database.</li>

   <li>Editing must be done on a different page <strong>Bracket failure if not on a seperate page</strong></li>

  </ul></li>

 <li>Bracket 6

  <ul>

   <li>Enable the user to select the features to query by using checkboxes (or similar)</li>

   <li>enable querying of the database using a boolean combination of user selected features.</li>

  </ul></li>

 <li>Bracket 7  Add in a form that permits the user to choose two GPUs for comparison purposes.

  <ul>

   <li>When the comparison is triggered a seperate page should be displayed</li>

  </ul></li>

</ol>

<strong>Bracket Failure if not seperate page</strong>

<ul>

 <li>The feature by feature comparison of both GPUs should be shown on the seperate page.</li>

</ul>

<ol start="8">

 <li>Bracket 8

  <ul>

   <li>UI design: well thought out UI that is easy and intuitive to use.</li>

  </ul></li>

</ol>