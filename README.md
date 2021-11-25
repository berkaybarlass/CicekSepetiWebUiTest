# CicekSepetiWebUiTest
 
📌 **Selenium Java Test Automation Project** 📌
 
   The basic testing methodology was used.
   
   **TEST1**
   
  ➾ **productFilterTest**
  >User goes to www.çiçeksepeti.com
  >>Click on "chocolate" from the most searched words.
  >>>On the page that opens, it filters the price to a maximum of 50 TL.
  >>>>After the products are filtered it checks the url from the filter's tag.
  >>>>>If the filter is over 50 TL, it will give an error.

➾ **clearHistory**
  >User goes to www.çiçeksepeti.com
  >>Click on "chocolate" from the most searched words.
  >>>First, shoes are searched on the search bar.
  >>>>Then the shirt is searched.
  >>>>>Finally, the pants are searched.
  >>>>>>The user then clicks on the "Clear History" button when they clear the search bar and click.

  **TEST2**
  
  ➾ **singUp**
  >User goes to www.çiçeksepeti.com
  >>Hover over the Sign in button and click the sign up button.
  >>>Fills in the required information completely.
  >>>>Sees and validates the thank you message.
  
  ➾ **successfulLogin**
  >User goes to www.çiçeksepeti.com
  >>Hover over the Sign in button and click the sign in button.
  >>>Fills in the membership information completely and clicks the login button.
  >>>>My "account" using login is verified.

  
