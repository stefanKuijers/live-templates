live-templates
==============

Introduction
--------------
This is a way to make live.js work with templates. It's basically live.js with a bit of added functionality. When editing templates the script detects or the template has been modified since the page was last loaded. If it was it reloads the page automagically. The only thing you have to do is add the base path to your router in this script and you are ready to go.

How to use
--------------
This is almost the same as live.js
   - get script & save
   - change the routerURL on line 27 to the url of your router
   - include script on the page(s) where you require live reload 

Disclaimer
--------------
Tested with Ionic and Angular. Should work with many other front-end frameworks eventhough it now only recognizes templates with .html or .jade

Credits
--------------
Of course the credits go to Martin Kool who made live.js
Checkout: http://livejs.com/

License
--------------
MIT License http://en.wikipedia.org/wiki/MIT_License  
IN SHORT: It's free. You can use it commercially. Don't sue us.
  
Copyright (C) 2014 by Stefan Kuijers
  
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE