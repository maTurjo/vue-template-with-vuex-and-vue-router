Technologies Used:
-------------------
The app is built on a SPA(single page application) architecture with no backend.

I've used Vuejs framework for this project,
with the official Vuex4 library for state management
and Vue Router 4 library for routing purposes.


Instruction to setup environment:
----------------------------------


Having NodeJs installed in the machine is a prerequisite for using the app.
Install node from "https://nodejs.org/en/" if you have not installed Node previously.

run the command line ""npm install"" in the project directory.
Then run the command line ""npm run serve"" in the project directory to setup the environment.


Test Scenarios:
---------------

visit the address given by the npm run serve command, usually "http://localhost:8080/" (yours can be different if ports are not available).
The landing on initiation creates the local storage data if it is not already created 
with id,size,color and price.

the landing page gives you the option of selecting the size and color of a specific shirt.
once the customer has selected both the size and color the add to cart options gets available.

customer can visit the cart from the navigation bar to visit the orders in cart.
You can delete the items from the basket.

Enough console logs are added to track the behaviour of the app in case of debugging.

Any Changes done manually in the code to manipulate the  session and local storage needs the manual deletion of the storages for changes to take place. 


Expected Enhancements:
----------------------
1.A full fledged payment portal integration can be done with more time and effort.
2.An initial landing page to direct customers to the items page can also be done .


Enhancements Done:
----------------

1.The notification feature when item is added to cart is an extra feature.
2.The colors demo markup in the display page which changes with the selection of color in the landing page. 