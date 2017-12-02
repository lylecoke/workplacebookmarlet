# workplacebookmarlet
Workplace bookmarlet to enable easy one button publishing of any web page from a web browser to Workplace

ShareOnWorkplace-Bookmarklet.html
This HTML page contains a Bookmarklet that once dragged to your Bookmarks bar allows you to post any web page to Workplace.
Download the file, then open it with your browser and drag the Workplace image to your Bookmarks bar.

posttoworkplace.js
This is a raw javascript that enab le the bookmarket shortcut to work.

javascript:(function(){    url = 'https://work.facebook.com/sharer.php?display=popup&u=' + window.location.href;    options = 'toolbar=0,status=0,resizable=1,width=626,height=436';    window.open(url,'sharer',options);})();
