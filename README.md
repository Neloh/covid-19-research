# covid-19-research
Research carried out on the released data sets and News updates on the pandemic Corona Virus 2019 (known as covid-19)

## The map
It was constructed in Python using a library 'folium' that allows one to build html based maps. 
The html map was deployed as a php application.

## To deploy 
We used heroku which uses git based commands. 
Firstly, login to heroku with credentials on CLI:
`heroku login`
Create the app after you have git add and commit 
Add files
`git add .`
Now commit all changes
`git commit -m "updated message"`
Now, create the app name on Heroku repo:
`heroku create`
Push the commits made:
`git push heroku master`

# The App:
Visit the URL: https://thawing-badlands-18701.herokuapp.com/
