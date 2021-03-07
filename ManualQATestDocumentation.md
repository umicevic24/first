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



# Auto apply (Additional scenarios)



|Steps                            |	Actions                                          |
|---------------------------------|---------------------------------------------------------------------------------------------------|
|1|	Open Chrome Browser and click on JoinMango Plugin|
|2|	Click on Search Icon|
|3|	Search a store|
|4|	Find a store that has an afiliate link|
|5|	Validate if the links lead to proper website|
|	|******************************************************|
|	|Search and Affiliate links validation (scenario above)|
|	|******************************************************|
|1|	Open Chrome Browser and go to store which is not supported by JoinMango|
|2|	Click on Join Mango Plugin|
|3|	Validate User should see a message "We don't support this website at the moment. If you think this store should be added, let us know and we'll add it as soon as possible."|
|4|	Click on Submit Request|
|5|	"Validate request should submit successfully and user should get message "Thank you! Our team is working on it and the store will be added to Mango shortly!"|
|6|	Validate JoinMango should receive request to add the store|
|7|	Click Done Button. 'Validate user should go back to JoinMango plugin home page|
|	|******************************************************|
|	|"Submit Request to add a Store (scenario above)"|
|	|******************************************************|
|1|	Open Chrome Browser and leave Address bar empty (don’t search for any store)|
|2|	Click on Join Mango Plugin|
|3|	Validate User should see a message "We don't support this website at the moment. If you think this store should be added, let us know and we'll add it as soon as possible."|
|4|	Validate "Submit Request" link should be missing|
|	|************************************************************************************************|
|	|"Submit request" link should be missing if Browser Address bar is empty (scenario above)|
|	|************************************************************************************************|
|1|	Open Chrome Browser and go to store (for ex: https://en-ae.namshi.com/) which is supported by JoinMango|
|2|	Click on Join Mango Plugin|
|3|	Validate User should not see a message "We don't support this website at the moment. If you think this store should be added..."|
|4|Validate user should not see "Submit Request" link|
|5|	Validate JoinMago Plugin should display the valid discount codes for the store|
|6|	Validate JoinMango should not display expired codes|
|	|************************************************************************************************|
|	|"Submit request" link should be missing if store is already supported by JoinMango  (scenario above)|
| |************************************************************************************************|


# Standard Cashback scenario



|Steps                            |	Actions                                          |
|---------------------------------|---------------------------------------------------------------------------------------------------|
|1|	Find the store for which we have affiliate link and open it, notice which affiliate network is used|
|2|	Click five-ten times anywhere on the page|
|3|	Validate that a new tab with the same store and a affiliate link has opened|
|4|	Go to that new tab and that store|
|5|	Add some low cost items and go to the checkout|
|6|	write TESTDEMOTEST on every field you can and click next|
|7|	For the payment option choose "Cash on delivery" if that is not available find another store|
|8|	Validate thank you page has showed up and take and save screenshot|
|9|	Wait for a day, than go to appropriate affiliate network site and in look in reports to find your transaction|
|10|	Go to our Database and check whether the same transaction with the same data (sub_id, cashback value...) is present|

# Language checking



|Steps                            |	Actions                                          |
|---------------------------------|---------------------------------------------------------------------------------------------------|
|1|	Install and pin the correct version of the plugin|
|2|	Go to the any selected store that has Arabic language option|
|	|**************************************************************|
|	|If the store is supported and there are codes available:|
|	|**************************************************************|
|1| Validate that the search page is using Arabic language and that no strange non-Arabic signs are present|
|2|	If the time is not of essence, take the screenshot of the page so it can be easily accessible later|
|3|	Validate that the pop-up landing page is using Arabic language and that no strange non-Abaric signs are present|
|4|	If the time is not of essence, take the screenshot of the page so it can be easily accessible later|
|5|	Click apply coupons button|
|6|	Validate that the loading coupons pop-up is using Arabic language and that no strange non-Abaric signs are present|
|7|	If the time is not of essence, take the screenshot of the page so it can be easily accessible later|
|8|	Wait for the final message and the ending of the auto-apply process|
|9|	Validate that the final message is using Arabic language and that no strange non-Abaric signs are present|
|10|	There are two possible messages in the outcome, positive and negative, try accesing stores with both versions to verify if both versions are using Arab language and no |
|| strange non-Arabic signs are present|
|11|	If the time is not of essence, take the screenshot of the page so it can be easily accessible later|
|	|****************************************************************|
|	|If the store is not supported or there are no codes available:|
|	|****************************************************************|
|1|Validate that the search page is using Arabic language and that no strange non-Arabic signs are present|
|2|	If the time is not of essence, take the screenshot of the page so it can be easily accessible later|
|3|	Validate that the pop-up landing page is using Arabic language, no coupon message and link to refer to one  is there and that no strange non-Abaric signs are present|
|4|	If the time is not of essence, take the screenshot of the page so it can be easily accessible later|
|5|	click  "refer the code link"|
|6|	Validate add coupon page is there and that is using Arabic language and that no strange non-Arabic signs are present|
|7|	If the time is not of essence, take the screenshot of the page so it can be easily accessible later|


# Login Scenario



|Steps                            |	Actions                                          |
|---------------------------------|---------------------------------------------------------------------------------------------------|
|1|	Click on the Mango sign in page|
|2|	Click join with google|
|3|	Click sign-in|
|4|	Select your e-mail account and click sign-in|
|5|	Validate you are signed in page has appeared|
|6|	Validate that in database there is recored with the same e-mail and correct info|
|	|******************************************************************************|
|1| Click on the Mango sign in page|
|2|	Click join with facebook|
|3|	Click log in and enter your facebook credidential|
|4|	Validate you are signed in page has appeared|
|5|	Validate that in database there is recored with the same e-mail and correct info|
|	|******************************************************************************|
|1|	Click on the Mango sign in page|
|2|	Click Join with e-mail|
|3|	Validate that the every field in form looks good|
|4|	Enter your info|
|5|	Validate that in database there is recored with the same e-mail and correct info|


# Search testing Scenario

|Steps                            |	Actions                                          |
|---------------------------------|---------------------------------------------------------------------------------------------------|
|1|	Open the search page and get to the search field|
|2|	Validate placeholder text (displayed within the search box and disappear when you start typing) is enabled|
|3|	Validate you are able to see each and every feature of Search in responsive mode, it must be mobile friendly|
|4|	Validate when you click on the search bar previous searches are presented|
|	||
|1|	Enter one after another in the search correctly spelled with small captions|
|2|	Enter one after another in the search correctly spelled with small captions|
|3|	Validate all of them appeared|
|4|	Validate the suggestions are properly updated when you enter/remove a keyword|
|5|	Validate links present are opening the correct stores|
|6|	Validate img of the results are responsive and mobile friendly|
|	||
|1| Select ten most important stores|
|2|	Enter one after another in the search correctly spelled with large captions|
|3|	Validate all of them appeared|
|4|	Validate the suggestions are properly updated when you enter/remove a keyword|
|5|	Validate links present are opening the correct stores|
|6|	Validate img of the results are responsive and mobile friendly|
|	||
|1|	Open the search page and get to the search field|
|2|	Enter string with random characters like "!#@$%^&"|
|3|	Validate no results wave been found|
|	||
|1|	Open the search page and get to the search field|
|2|	Enter H&M |
|3|	Validate that the store has appeard|
|4|	Remove the entry|
|5|	Enter B&B|
|6|	Validate that the Bath and Body store has appeard|
|7|	Remove the entry|
|8|	Enter "123"|
|9|	Validate that there are stores present|
|10|	Remove the entry|
|	||
|1|	Open the search page and get to the search field|
|2|	Enter double "a" sign|
|3|	Validate that names of the stores have no strange unarticulated signs|
|4|	Remove the entry|
|5|	Enter double b|
|6|	Validate that names of the stores have no strange unarticulated signs|
|7|	Remove the entry|
|8|	Go trough entire alphabet and validate the same results|
	





