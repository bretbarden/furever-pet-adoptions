FUREVER PET ADOPTIONS

BACKGROUND:
FurEver is a website that lets users find pets for adoption. Following the pet adoption boom
of the COVID pandemic, there has been an unprecedented number of pet being given back now 
that pandemic is over. FurEver helps these pets find their FurEver home.

![FurEver site display](/assets/furever-pet-adoptions.png "FurEver Pet Adoptions")


GIT REPOSITORY:
The git repository for this website is available at
https://github.com/bretbarden/furever-pet-adoptions

RUNNING THE JSON SERVER:
Once the git repository is cloned to your machine, run the json server with the following command:
    $ json-server --watch db.json

STARTING THE FRONT-END:
Once the JSON server is running, start a new terminal, and open the index.html file:
    $ open index.html
This should load the site in your browser.


HOW TO USE THE SITE:
1. The page will load with a random pet in the right details pane
2. You can search for pets by species, breeds, age, and gender using the search bar
3. Click on a pet square to display details about the pet in the right side pane
4. When you "lick" a pet, a form will pop up requesting the users info as a potential adoptee
5. Upon form submission, the site will thank the user and reset, while saving the user's info to the server

