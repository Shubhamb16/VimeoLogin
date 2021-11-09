# VimeoLogin
# This Project is based on the verification of Comment on the video added from API
# Install below tool required for the project
   - Katalon Studio
# Create a account in Github
# Create a new account in vimeo app and create an dummy app and register
# Get Access token from the -https://developer.vimeo.com/apps/230544#generate_access_token
# Login to katalon studio and create a API request
# Login to vimeo through API (email,password and access token)
# Select video from API and provide a comment
# Now create a Test scrit in katalon studio with below scenarios
   - Open browser and navigate to https://vimeo.com/
   - login to vimeo from valid credentials
   - go to browse videos and select a video
   - play video 
   - now verify the comment on the video from UI which is added from API
   - Navigate to anyother video
   - Save Number of likes as Test case variable
   - Save Number of Views as Global variable
# Created a BDD Test framework for above steps and added validation for each step
# Created a Feature file, feature folder and executed from katalon
# Created a Test Suit and executed frtom katalon studio

# Login From API
   - Created user in vimeo app and also registered dumy Application
   - Creates Acces token
   -  Autherize URL- https://api.vimeo.com/oauth/authorize
   -  Access token- https://api.vimeo.com/oauth/access_token
   -  Added Access token into header and tried login to vimeo app with katalon API and also Postman
   -  I am getting 401- unauthorize error everytime i am trying to hit the URL through API
 # Reason
    - I did some research and it looks the API is showing unauthorize error due to below 2 reasons
    1. Because of Cross Environment check
    2. API might try to create some extra autogenrated headers by hitting API which i am unaware of.
# So i am not able to do vimeo action through API
# I have attached a zip file in Github repo as i am facing some issue with the cloning of my project in Github so i have manually created a zip file and attached
# Please extract the zip file and go through the project
 - https://github.com/Shubhamb16/VimeoLogin.git
