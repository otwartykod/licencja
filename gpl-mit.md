# GPL vs MIT

+  If you want to restrict the use of your modifications, then MIT is able to be more restrictive than the GPL for distribution and that might be what you're looking for.
 
 + In case you want to ensure that the freedom of your software does not get restricted that much by the users you distribute it to, then you might want to release under GPL instead of MIT.

## For both licenses

+ Free Redistribution
+ Source Code
+ Derived Works
+ Integrity of The Author's Source Code
+ No Discrimination Against Persons or Groups
+ No Discrimination Against Fields of Endeavor
+ Distribution of License
+ License Must Not Be Specific to a Product
+ License Must Not Restrict Other Software
+ License Must Be Technology-Neutral


## Including

+ If you include GPL licensed code in a MIT licensed product you will at the same time include a MIT licensed product in GPL licensed code as well


### If You not include GPL code in a MIT licensed product:

If you distribute a combined work that combines GPL and MIT code that distribution must be compliant with the GPL.


## If You can include MIT licensed code in a GPL product:

The whole combined work must be distributed in a way compliant with the GPL.
If You have made changes to the MIT parts of the code, you would be required to publish the source for those changes
if you distribute an application that contains GPL and MIT code.

If you are the copyright owner of the GPL code, you can choose to release that code under the MIT license instead - in that case it's your code and you can publish it under as many licenses as you want.

## Dependencies

Adding a GPL dependency does not change the license of your code but it will limit what people can do with the artifact of your project. This is also why the ASF does not allow dependencies to GPL code for their projects.


## Result of using GPL part of code:

You don't have to open-source your changes if you're using GPL. 

You could modify it and use it for your own purpose as long as *you're not distributing it*. 

BUT... if you DO distribute it, then your entire project that is using the GPL code also *becomes GPL automatically*. 

Which means, it must be open-sourced, and the recipient gets all the same rights as you - meaning, they can turn around and distribute it, modify it, sell it, etc.

And that would include your proprietary code which would then no longer be proprietary - it becomes open source. 


## Result of using MIT part of code:

If you actually distribute your proprietary code that is using the MIT licensed code, 
You do not have to make the code open source. 
You can distribute it as a closed app where the code is encrypted or is a binary. 

Including the MIT-licensed code can be encrypted, as long as it carries the MIT license notice. 

