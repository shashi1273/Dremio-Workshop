+++
title = "Creating the Dremio CloudFormation Stack"
chapter = true
weight = 1013
+++

<div style="text-align: justify">
    <center><h2>Creating the Dremio CloudFormation Stack</h2></center>

   <br/><br/>
       
       <ol>
           <li>Create Stack</li>
            <br/>
           Ensure the following options are checked to mirror the image below.  *Note* that the Amazon S3 URL will be different from the example.  Once the correct options are checked, click next at the bottom of the screen. 
<img src="../../images/dremio6.png" style="margin:15px 0px; border:1px solid black"/>
           <li> Specify Stack Details </li>
            <br/>
           
  Provide a Stack Name.  An example would be <b>Dremio-Modernization-Workshop</b>
           
Make your selections as per the image below.         
   
   <img src="../../images/dremio7.png" style="margin:15px 0px; border:1px solid black"/>
  <li>Configure Stack Options</li>
     For this page, you do not need to add anything additional, continue by pressing next at the bottom of the screen
 <br/>
<li> Review Stack  </li>
Review the inputs and make sure they match the steps above.


At the bottom of the screen under “Capabilities” click that the check box that acknowledges that CloudFormation might create IAM resources.
 <br/>
Once finished, press next at the bottom of the screen. Select the acknowledgment check box and click <b> "Create Stack"</b>

 <br/>
Now you should see the CloudFormation Status say “CREATE_IN_PROGRESS”

<img src="../../images/dremio8.png" style="margin:15px 0px; border:1px solid black"/>

It should take approximately 2 minutes to create the stack.  Once the stack is completed, the status will change to CREATE_COMPLETE.  Once the stack has been created, navigate to the “Outputs” tab under the name of your CloudFormation Stack
      <img src="../../images/dremio9.png" style="margin:15px 0px; border:1px solid black"/>
      
From the <b>“Outputs” </b> tab, you should see the DremioPublicEndpoint which will be an IP Address.  Click the IP Address to launch Dremio
      <img src="../../images/dremio10.png" style="margin:15px 0px; border:1px solid black"/>
       </ol>

   




</div>
