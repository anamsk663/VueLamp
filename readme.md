Errors ::

There's a typo in getElementById (it's written as getElementbyId)
The light toggle is using incorrect syntax: classList.on("on") should be classList.toggle("on")
The light variable is not properly defined

Fixes :: 

I've fixed the following issues in the JavaScript code:

Corrected getElementbyId to getElementById
Properly defined the light variable by getting the element with ID "light"
Changed classList.on("on") to classList.toggle("on")
The toggle button should now work correctly. When clicked, it will:

Toggle the "active" class on the button
Toggle the "on" class on the light image
