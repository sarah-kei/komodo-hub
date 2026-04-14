# komodo-hub
Komodo Hub is a second-year Computer Science team project focused on educating users about endangered species through interactive features. I developed the student dashboard and implemented a gamified badge and scoring system, rewarding users for wildlife sightings, with higher points for rarer species.

WEBSITE SETUP



<p align="center">
  <strong>KOMODO HUB WALKTHROUGH</strong>
</p>


<p align="center">
  <a href="https://youtu.be/R-D4CS3DcO4">
    <img src="https://img.youtube.com/vi/R-D4CS3DcO4/0.jpg" width="700" alt="Watch the Komodo Hub Demo">
  </a>
</p>




Click the image above to watch the Komodo Hub demonstration on YouTube.




CLONE REPOSITORY 

    git clone https://github.coventry.ac.uk/rudzinskao/5005CMD-Group-Project.git 
    cd 5005CMD-Group-Project 

CREATE A VIRTUAL ENVIRONMENT  

   FOR WINDOWS  

        python -m venv venv 

 
   FOR MAC 

        python3 -m venv venv 


ACTIVATE ENVIRONMENT  

   FOR WINDOWS  

        .\venv\Scripts\Activate.ps1 

NSTALL REQUIRED PACKAGES  

    pip install -r requirements.txt 

DEACTIVATE ENVIRONMENT WHEN DONE 

    Deactivate 

RUN PROGRAM 

    flask run 
    Link: http://127.0.0.1:5000 

INSTRUCTION ON HOW TO USE APP 

    First entering the page as a guest user you are able to: 
    
    View the Home page (‘Home’ in navigation bar at the top of page) 
    
    View the about page (‘About’ in navigation bar) 
    
    View the Forums main page (‘Forums’ in navigation bar) 
    
    View existing Forums (under ‘community libraries’ in ‘Forums’ page) 
    
    View members within the forum in the members list 
    
    Filter content in the forums for relevant information using the tags above the content. Labelled ‘All’ ‘General’ ‘Discussion’ ‘Social’ ‘Questions’ ect. This       will show posts made using this tag. ‘All’ shows       all content in the library. 
    
    Register an account (‘Register’ on the right of the navigation bar): 
    
    Input an unused email (must have ‘@’ character and be unique to be valid) 

    Input valid username 

    Create a secret password 

    Login to an existing account (‘Sign in’ on the right of navigation bar) 
    
    Input valid username 
    
    Input valid password 
    
     
    
   Logged-In users  
    
    Inherit all permissions from guest user 
    
    Visit profile (User icon at the top right of navigation bar) 
    
    user can add profile picture and gain badges (hoover to see tootip showcasing note) 
    
    View the Games page (‘Games’ in the navigation bar) 
    
    Access the games with graphic buttons ‘Memory Match’ and ‘Trivia Quiz’ 
    
   Memory Match game:  

    Click two tiles and try to match the animals on the other side. 
    
    Match number is displayed at the top 
    
    Restart button is displayed at the top. Press to restart game 
    
    When game is won, pop up of ‘You Won!’ displays. Press restart game to play another roung 
    
   Trivia Quiz game: 
    
    Empty page with ‘coming soon’ in container. No functionalities here 
    
    When viewing a created Library found in ‘forums’, you can request to join this library using the ‘Request to Join’ button in the left information sidebar of       the library. 
    
    This sends a request to the owner of the library (Shown in information labelled created by: ) 

    Shows ‘request pending’ until owner accepts your request.  
    
    When accepted, the display will show ‘You are a member’ and your profile and username shows up in the members list in the information section. 
    
    Being a member of the community allows the user to: 
    
    Create a text post (input text into the text area. You must select a tag relevant to your post from the dropdown under your username). Press ‘post’ button to      submit 
    
    Add media to your post by clicking the image button under the text area box. Press ‘post’ button to submit 
    
    Like posts using the heart button displayed under the post 
    
    Save posts to the right hand side of your library page. This content will stay across all libraries so you can see your favourite or crucial information. 
    
    Comment on posts using the text area under the post 
    
    Leave the community by using the ‘Leave community’ button in information on the left side bar. 
    
     


   Admin Users: 
    
    To gain access to admin tools, create an account and go to profile, where underneath the profile picture you can enter the code “admin” in a real-world case       this would be a secret key hidden from the user-       facing front end, but to test the code is admin.  
    
    Inherit all permissions from Logged-in users 
    
    Able to create libraries using the ‘Create library’ form in ‘forums’ in the navigation bar. Input the name, title and description of your community for others     to learn more. 
    
    Once creating your own library, you are listed as the ‘Owner’ under the information on the left-hand side of the page. You also instantly have permission to       post, like, save and comment 
    
    If a user requests to join your community, they will be displayed in the ‘Pending requests’ section within information. You are presented with an ‘accept’ or      ‘deny’ function to control who joins the forum. 

    When logged in as admin, a button “Admin” appears on the navbar, which takes the user to the admin settings page, here you can enter a school’s name, number       of people involved with the school, and an expiry      date to create a school code, 
    
    A school code should be copied, and sent to the school, but for testing purposes just create another account and use the code in the profile page. 
    
    The first user to use the code will be given the teacher role, and from there everyone else will be “student”. 
