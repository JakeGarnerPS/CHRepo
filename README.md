# CHRepo
To run this project. 

Unzip project. 

Open project with your coding application. I used IntelliJ. 

- Build/Rebuild the project. 

- Open terminal make sure the terminal is using GIT bash. 

- Enter the following: 

	'npm run json:server'

- If this returns localhost:3000, then it has worked. 

- Open an internet browser and enter the url: http://localhost:3000/Games/1
	- This will display the value for game 1 (Part 1)
	- You can also cycle through all the games in the json file

- The console  will also diplay all the games listed in the json file  http://localhost:3000/Games (Part 1)

- If you want to add your own data to the json list, you can use Postman(or similar) and a post request.
E.g 
POST: http://localhost:3000/Games
	{
      "title": "Command & Conquer Generals",
      "description": "RTS",
      "by": "EA",
      "platform": [
        "PC"
      ],
      "age_rating": "15",
      "likes": 600,
      "Comments": [
        {
          "user": "commanderShep",
          "message": "Best RTS about",
          "dateCreated": "2006-03-21",
          "like": 43
        }
      ]
    },

NOTE: all other REST commands should also work 

Part 2

- Once the run has completed, it should open a webpage http://localhost:3000/Reports, which should display the information requested for Part2. 
	Can also be seen in the console.



