# Robot Framework with Selenium Library, Imap Library, and Page Object Model
### [Overview of the project](https://github.com/mvecina25/amazon_with_robot_framework/blob/master/Overview.docx)

#### Automate the following:
- Login
- OTP
- Selection of cart
- Adding items to cart
- Checkout for payment option
- Logout

#### Pre-requisite
1. Install Chrome
2. Install JDK (java version 11.0.2)
3. Install Python (version 3.7.1)
4. Install the following by running this command: 
      ```sh
      pip install robotframework
      pip install robotframework-seleniumlibrary
      pip install robotframework-sikulilibrary
      pip install robotframework-pabot
      pip install robotframework-imaplibrary
      ```
5. Set System Variables: 
      ```sh
      JAVA_HOME "C:\Program Files\Java\jdk-11.0.2" 
      PATH C:\Users{username}\AppData\Local\Programs\Python\Python37-32\Scripts 
      PATH C:\Users{username}\AppData\Local\Programs\Python\Python37-32
      ```
#### How to run
      1. Run CMD
      2. Go to the location of the project
      3. Type "robot iselect-amazon\test-suites\EndToEndTest.robot"
      
> Project for iSelect
