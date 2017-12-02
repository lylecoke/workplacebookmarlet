# workplacebookmarlet
The Workplace bookmarlet was created to enable easy one button publishing of any web page from a web browser to Workplace.  This will allow greater levels or particpation and adoption by making it rediculously easy to post new and engaging content to Workplace.

ShareOnWorkplace-Bookmarklet.html

This HTML page contains a Bookmarklet that once dragged to your Bookmarks bar allows you to post any web page to Workplace.
Download the file, then open it with your browser and drag the Workplace image to your Bookmarks bar.

posttoworkplace.js

This is a raw javascript that enab le the bookmarket shortcut to work. Create a new shortcut on the Bookmarks bar and copy and past the code from the posttoworkplace.js file in to the URL field.  Give it a name like Post to Workplace and save.

javascript:(
function(){    
url = 'https://work.facebook.com/sharer.php?display=popup&u=' + window.location.href;    
options = 'toolbar=0,status=0,resizable=1,width=626,height=436';    
window.open(url,'sharer',options);})();

Lyle Edwards | 
Enterprise Architect | 
Collaboration, Employee Expereince, HR, DevOps, IT Tools | 
The Coca-Cola Company

Dec 02, 2017

