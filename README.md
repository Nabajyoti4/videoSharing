#project-VSA
<!-- install video.js -->
npm install video.js
........................................................................
New AOS library added

1) style sheet link
 <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
 
 
2) script source 
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  
3) To initiate the AOS
 <script>
    AOS.init();
</script>
.........................................................................
signin form id's:
------------------
 signin_email
 signin_passwd
 create_account
 forget_password
 button--> signin


..........................................

 Signup form:
------------------
 singup_firstname
 signup_lastname
 signup_email
 signup_number
 signup_passwd
 signup_confirm_passwd
 SIGNUP BUTTON: signup

............................................
 ID's
------------------
 upload button: upload-video
  <!-- for title -->
<input type="text" class="form__input--upload form__input--upload--1" id="upload-title"
                    placeholder="Title">
                <!-- for description -->
<textarea rows="2" cols="30" class="form__input--upload form__input--upload--1" id="upload-description"
                    placeholder="Description"></textarea>
............................................
 static images sources
------------------

rocket ->"img/icons/rocket.png"
man ->"img/icons/man.png"
title icon ->"img/icons/avatar.png"

login anchor tags:-
------------------
          <!-- create button -->
          <a href="signup.html" class="btn btn--white" id="create_account">Create Account </a> &nbsp;<span class="btn" >&nbsp;nbsp;</span>


signup anchor tags:-      
<a href="login.html" class="btn btn--white"  id="signin">Login</a>
<!-- for now the signup is created using float next update will be done by using grid property -->

home anchor tags:-
------------------
              <a href="home.html" class="navbar_items">Vidshare </a> 
              <li><a href="login.html" class="btn btn--front">login</a>
                      <a href="signup.html"  class="btn btn--front">Signup</a></li>

close button in upload page
-------------------              
             <a href="#headSection" class="btn--close">&times;</a>

...............................................................................................................................
setting page button id's
----------------------
<span class="accountHolderName">Raju</span>
<span class="accountHolderId">cs16msiit020@gmail.com</span>

change password Button section
---------------------------------
img background source=> "/img/back-3.jpg"
profile image=>  "img/icons/man.png"
   
edit profile image button =>id "edit_profileimage"
submit button -> id="changePasswordBtn"

current password  textfield ->     id=  "current_passwd"
new password  textfield ->    id=   "new_passwd"
new password(confirm)  textfield ->    id=  "new_confirm_passwd"



user profile
------------------
logout button id =logoutButton

..........................................................................
 play video page
  id="video-title"
  id="video-description"
...........................................................................
forgot password IDs
 
forget password->forget_passwordBtn
OTP input ->otp_field
Confirm otp button ->submit_otp

............................................................................
>>slide show in header images source
------------------
img1->"img/event-2.jpg"
img2->"img/head.jpg"
img3->"img/col.jpg"

>>info section-->
------------------
img1->"img/head1.jpg" 
img2->"img/event1.jpg"
img3->"img/floor1.jpg"




......................................................
 
 New background image in the feature section.
 
 backgorund- image use at  ->  ( _home.scss in feature section part line no. 33)
 image name ->  "img/head.jpg"
 
 ........................................................

 New background image in footer

 background-image -> _footer.scss ( at line no. 8)
 image name -> "img/foot.jpg"
 

..................................................
Grid used for the story section with 3 cards view

.story > main section grid name with 2 rows

.cardsgrid > grid for the cards dyanmic row and column
