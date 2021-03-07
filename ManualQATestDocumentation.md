# Auto apply (Main Thread Scenario)

|Steps                            |	Actions                                          |
|---------------------------------|---------------------------------------------------------------------------------------------------|
|1	                              |Install and pin the correct version of the plugin                                                  |
|2	                              |Go to the any selected store                                                                       |
|3	                              |Validate that the store is supported                                                               |
|4	                              |Validate that there are codes available                                                            |
|5	                              |Validate if the store logo is present and if it has proportional witdth and height                 |
|				      |************************************************************************************************** |
|1				      |Install and pin the correct version of the plugin|
|2				      | Go to the any selected store|
|3	                              | Add couple of items to the cart|
|4	                              | Go to cart page|
|5	                              | Validate that there is coupon field present|
|6	                              | Validate that Mango/Minty pop-up has appeared|
|7	                              | If not, validate that auto-apply button is present in the Mango/Minty extension pop-up page|
|				      |************************************************************************************************** |
|1				      |Install and pin the correct version of the plugin|
|2	                              | Go to the any selected store|
|3	                              | Add couple of items to the cart|
|4	                              | Go to checkout page|
|5	                              | Validate that there is coupon field present|
|6	                              | Validate that Mango/Minty pop-up has appeared|
|7	                              | If not, validate that auto-apply button is present in the Mango/Minty extension pop-up page|
|				      |************************************************************************************************** |
|1	                              | Install and pin the correct version of the plugin|
|2				      | Go to the any selected store|
|3				      | Add couple of items to the cart|
|4				      | Go to cart page|
|5				      | Validate that there is coupon field present|
|6				      | Validate that Mango/MInty pop-up has appeared|
|7				      | If not, validate that auto-apply button is present in the Mango/Minty extension pop-up page|
|8				      | Start auto-apply proccess|
|				      |
|	While auto-apply is running:  |
|	 			      |
|1	|Validate that codes have been entered in the field|
|2	|Validate that codes are not being skipped|
|3	|Validate that codes have been applied|
|4	|Validated that the process has finished properly withouth interruption|
|	|								       |
|If the Store total price shows that coupon has been found|
|	||
|1	|Validate that Minty/Mango coupons are present and selected|
|2	|If not validate that from the other coupons the best coupon has been selected|
|3	|Validate that the proper last message is present|
|4	|Validate that the name of the coupon in the last message is the same as the coupon applied in the store|
|5	|Validate that the value of coupon is the same as the value applied in the store|
|	||
|If the coupon has not been found|
|	||
|1	|Validate that the corect message has been presented|
|2	|Validate that the "continue" and "x" button are working properly|
|3	|Manually copy the coupons and enter them in the field|
|4	|Validate that none of the coupons are valid|
|5	|Add more diverse selection of items in the cart|
|6	|Start auto-apply again|
|7	|After finish validate which of the coupons have been expired|
|	||
|Run the process again and validate if the results are the same!|
|	||
|	||
|Do the same for the checkout page:|
|	||
|1	|Install and pin the correct version of the plugin|
|2	|Go to the any selected store|
|3	|Add couple of items to the cart|
|4	|Go to checkout page|
|5	|Validate that there is coupon field present|
|6	|Validate that Mango/Minty pop-up has appeared|
|7	|If not, validate that auto-apply button is present in the Mango/Minty extension pop-up page|
|8	|Start auto-apply proccess|
|	||
|While auto-apply is running:|
|	||
|1	|Validate that codes have been entered in the field|
|2	|Validate that codes are not being skipped|
|3	|Validate that codes have been applied|
|4	|Validated that the process has finished properly withouth interruption|
|	||
|If the Store total price shows that coupon has been found:|
|	||
|1	|Validate that Minty/Mango coupons are present and selected|
|2	|If not validate that from the other coupons the best coupon has been selected|
|3	|Validate that the proper last message is present|
|4	|Validate that the name of the coupon in the last message is the same as the coupon applied in the store|
|5	|Validate that the value of coupon is the same as the value applied in the store|
|	||
|If the coupon has not been found:|
|	||
|1	|Validate that the corect message has been presented|
|2	|Validate that the "continue" and "x" button are working properly|
|3	|Manually copy the coupons and enter them in the field|
|4	|Validate that none of the coupons are valid|
|5	|Add more diverse selection of items in the cart|
|6	|Start auto-apply again|
|7	|After finish validate which of the coupons have been expired|
|	||
|Run the process again and validate if the results are the same:|
|	||
|	||
|	|Important notice: Be familiar with single page sites and implement the scenario on them as well!|


# Installation journey

|Steps                            |	Actions                                          |
|---------------------------------|---------------------------------------------------------------------------------------------------|
|1|	Open Chrome Browser and go to https://joinmango.co/|
|2|	Click on "Add to Chrome - It's Free" button|
|3|	On "Mango: Auto Apply Coupon Codes" Page, Click "Add to Chrome" button|
|4|	Validate "Add Mango: Auto-Apply Coupon Codes?" popup Should display to user|
|5|	Click Cancel|
|6|	Validate JoinMango plugin should not add to Chrome extensions|
|	||
|1|	Open Chrome Browser and go to https://joinmango.co/|
|2|	Click on "Add to Chrome - It's Free" button|
|3|	On "Mango: Auto Apply Coupon Codes" Page, Click "Add to Chrome" button|
|4|	Validate "Add Mango: Auto-Apply Coupon Codes?" popup Should display to user|
|5|	Click Add extension|
|6|	Validate JoinMango plugin should add to Chrome extensions|
|7|	Validate user lands on https://joinmango.co/install/ page and page should display message "Ready to shop & Save? "|
|	|******************************************************************************************************************|
|	||
|1|	Open Chrome Browser and go to https://joinmango.co/|
|2|	Validate once plugin added successfully to chrome extensions, user should not be asked to Add extension again|
|3|	Validate user should directly land on "Ready to shop & save?" page|
|	|
|	|******************************************************************************************************************|
||Re-adding Mango plugin extension|
|	|******************************************************************************************************************|
|1|Open Chrome Browser and go to Manage Extensions|
|2|	Click on "Remove" button for Mango: Auto-Apply Coupon Codes extension|
|3|	Validate a popup should display asking user "Remove Mango: Auto-Apply Coupon Codes?"|
|4|	Click Cancel|
|5|	Validate JoinMango plugin should not get removed from chrome extensions|
|	|******************************************************************************************************************|
|1 |Open Chrome Browser and go to Manage Extensions|
|2|	Click on "Remove" button for Mango: Auto-Apply Coupon Codes extension|
|3|	Validate a popup should display asking user "Remove Mango: Auto-Apply Coupon Codes?"|
|4|	Click Remove|
|5|	Validate JoinMango plugin should get removed successfully from chrome extensions|
|6|	User should land on page https://joinmango.co/uninstall|
|7|	Validate Page should ask users feedback "Help us improve"|
|8|	Select a reason to uninstall and click Submit|
|9|	Validate JoinMango should receive users feedback successfully and save in DB|
|	|******************************************************************************************************************|
||Remove Mango Plugin extension using Manage Extensions and vaidating cancel function|
|	|******************************************************************************************************************|
|1 |Open Chrome Browser and go to JoinMango.co|
|2|	Click on "Add to Chrome - It's Free" button|
|3|	User should land on chrome Web Store Page|
|4|	Click "Remove from Chrome" button|
|5|	Validate a popup should display asking user "Remove Mango: Auto-Apply Coupon Codes?"|
|6|	Click Cancel|
|7|	Validate JoinMango plugin should not get removed from chrome extensions|
|8|	Click Remove|
|9|	Validate JoinMango plugin should get removed successfully from chrome extensions|
|	|******************************************************************************************************************|
|	|"Remove Mango Plugin extension using ""Remove From Chrome"" button on Chrome Web Store Page|
|	|******************************************************************************************************************|






