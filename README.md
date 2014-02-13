## Overview

hangouts for command line on **Mac OS X**.



## Hangouts

[Hangouts](www.google.com/+/learnmore/hangouts/) brings one-on-one and group conversations to life with photos, emoji, and video calls for free. Connect with friends across computers, Android and iOS.



## Configuration
[Configuring](https://support.google.com/talk/answer/24076?hl=en) [Messages (iChat)](http://support.apple.com/kb/HT5395) for [Google Talk](http://www.google.com/talk/) 



## Usage
```
You can change the default receiver_name in the script.

hangouts [-u receiver_name] message


or from stdin with Ctrl-D end:

hangouts [-u receiver_name] 
```



## Sample
```
hangouts -u "John" Hi~ John!

cat /etc/mail.rc | hangouts -u John
```
