# pebbles-meta
Primary purpose is to manage multi-tiered repositories within the Pebbles MSE. Contains files leveraged for CI/CD, centralized documentation, and other useful files needed in the Pebbles MSE.

# Spring 2 Final Thoughts - 10/5/2018
Chinedu Ozodi | Spark1806-USF-Java | Steven Kelsey

This iteration has introduced the ability to hit server side endpoints properly from client side. There have been a lot of changes, including the addition of Boom client side which still needs to be fleshed out, and Splunk that is used for logging. Proper and more useful loggs need to be created to replace the current AOP logging server side, and a logging solution is needed for client side. There is a lot of code cleanup and optimization that needs to be done mainly client side. Most notable, there should no longer be a need for the user service since the cognito service is taking care of the user, and the user web service has been removed server side. Once the flow of information gets solidified client side, server side can be chnaged to have all the needed endpoints, and it will be one step closer to production
