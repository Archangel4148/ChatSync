# ChatSync
ChatSync: Effortlessly connect Groupme and Discord messages. Comprehensive documentation guides you through setting up a seamless real-time messaging stream. Enhance cross-platform communication with ChatSync for a unified chat experience. (Thanks ChatGPT :P)


Step 1: Find a method to link a single Groupme to a single Discord channel    
 -- Helpful Links:      
 https://dev.groupme.com/docs/v3 (Groupme API documentation)         
 https://dev.groupme.com/tutorials/bots (Basic bot setup tutorial)       


 Progress:   
  - Created a groupme bot using the official page, and connected it to a test group     
  - Utilized cURL to send the groupme API a request for the bot     
  - Got the bot to send a message in the group by using a terminal command     
  - Set up a basic Apache HTTP server on a virtual machine to (hopefully) test the bot's POST functionality (and log new messages)      
  - Tested the Apache server with more cURL POST requests, and successfully received a request from a remote computer       
  - PROBLEM: I can't seem to receive anything from the groupme API itself; Either it's not sending (invalid URL), or I just don't know how to properly recieve it... I need to go to sleep...        

