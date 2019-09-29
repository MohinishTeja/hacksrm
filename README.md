# SlackDown
#Team-  Sole Survivors<br>


Project Name--    SlackDown.<br>

  Problem Statement- <br>

  Slack provides a workspace with a capacity of 10k messages for free. If our messages exceed that limit our messages will be deleted automatically unless we upgrade to paid version.Hence, older chats can't be accessed after 10k messages.Our Aim is to access those older chats though JSON Dump Files.<br>
  
  Hence, we would like to use the JSON dump files provided by slack to recreate a interface that has all the old messages displayed in it. Further, we will be adding search option and Analytics to show the progress and trends happening in the workspace.<br>
  
  Use-<br>
  
  
  With this hack,we will be saving 3$ a month for every user in workspace.Consider a workspace of 100 members it costs 300$ a month for workspace.<br>
  Also, we are representing the extraction of JSON data which is the main source of data type using today in any web application.It transfers data between Server and users efficiently than previous version like XML.
  
  
  
  Slack JSON data is originally used to merge two workspaces but here we will be using it to recreate the entire conversation which makes this a unique project.<br>
  
  
  Tools/technologies we use - JavaScript,JS libraries,HTML,CSS.<br>
  
  Problems Faced-<br>
  1)JSON dump files from slack are highly complex to retrieve.  <br>
  2)JSON files of slack has n number of objects looped inside each other and finally in a array.<br>
  3)Though we can access the variables easily it is difficult to print it out to HTML because<br>
    a)Javascript has only two main ways to print out to HTML(getElementbyId and document.write).
  4)timestamp is not in human readable format.<br>
  5)making a interface from scratch.<br>
  
  
 Problem Solving techniques-<br>
 
 1)We used functions to convert epoch form of timestamp to human readable format.<br>
 2)We used HTML inside JS and again inside of HTML to get the data from JS function to HTML.<br>
 3) Used plotly method to generate graphs for the traffic of messages.<br>
  
  
