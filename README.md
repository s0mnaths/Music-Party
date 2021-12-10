
# Music Party

Easily collaborate in playing songs at a party!

## How?
1. Create a room & set the permissions.
2. Share the room code.
3. Play songs and let others vote to play/pause & skip!


## Demo
#### Create a Room
![create](demo/create-demo.gif)

#### Join a Room
![join](demo/join-demo.gif)


## Run locally

#### Spotify API access
![spotify](https://img.shields.io/badge/Spotify-1ED760?&style=for-the-badge&logo=spotify&logoColor=white)

1. Create a developer profile, and a new app on Spotify by going to [Spotify Developer Dashbboard](https://developer.spotify.com/dashboard/applications). 
2. In the app settings, set Redirect URI as `http://localhost:8000/`.
3. Copy the `CLIENT_ID` & `CLIENT_SECRET`, & paste it in the file `/path/to/repo/spotify/credentials.py`  file.



#### Backend 
![django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green) ![djangorest](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)

     $ cd path/to/repo/
     $ pip install -r requirements.txt   
     $ python manage.py migrate
     $ python manage.py runserver
        
#### Frontend
![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![material-ui](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)

    $ cd path/to/repo/frontend/
    $ npm install
    $ npm run dev

Now the app is live at `http://localhost:8000/`

### Enjoy! 🎊

