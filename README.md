High-level approach:
We implemented helps functions to carry out the functions like GET, POST, etc. In our main run method, we do the status code handling. We also overwrote the HTML parser class  available in python. We use this to find the links on a page and find the secret flags. Once we find the five secret flags, we break out of the while loop on our run method.  

Challenges you faced:
One of the main challenges was that we were not able to find the flags because we were parsing the same again and again. Our program was taking a lot of time to finish running. Another problem was that we were finding duplicate flags. So we tried to implement a way ot check for duplicates. 

Properties/features:
We used the skill of divide and conquer, by that we mean we abstracted functionalities into helper functions, which makes the structure of our code more concise and easier to debug. 

Testing:
We used print statements throughout the project to easily see which requests and reposnses were received.