# django-groupchat
Build a simple application which provides web services to facilitate group chat and manage data.


Steps to execute this code:
 1. git clone git@github.com:tapupadhi/django-groupchat.git
 2. navigate inside to your cloned directory
 3. create virtual environment and configured your python interpreter
 
 **Steps to create virtual environment:**
  go to folder containing project
  python3 -m venv env_name
  source evn_name/bin/activate
  now you will be able to see (env_name) infront of the each terminal line
  
  4. Now you can install required libraries in virtual environment: "pip3 install -r requirement.txt"
  5. python manage.py createsuperuser
      Username: provide of your choice
      Email address:leave it blank
      Password: provide of your choice
      Password (again): repeat the provided password
      
      Note: this is your admin user
  6. python manage.py runserver
  7. now open in web browser: "http://127.0.0.1:8000/admin"
      ![image](https://user-images.githubusercontent.com/48438852/228135970-fe195b9d-44eb-4472-b292-f934874eecaa.png)
  8. select on "Users"
      ![image](https://user-images.githubusercontent.com/48438852/228136177-fce1702f-c27d-490a-9232-ee507dc96ace.png)
  9. you can now add as many users as you want.
      ![image](https://user-images.githubusercontent.com/48438852/228136396-ae18eb0a-1ab0-42ae-948b-a748c09f780c.png)
      
      since you are creating norma users, you don't have to provide any other permissons(refer below snapshot)
      
      ![image](https://user-images.githubusercontent.com/48438852/228136805-10c6543c-4e58-4cdd-8614-05a69158f38a.png)
      
      now save. the you user got created.
      
      like this you can create many users.

      or,
      
      "http://127.0.0.1:8000/" here you can create user by signing up.
      
  10. Create Room:
      Select Rooms in admin panel and then click "add room" like below
      ![image](https://user-images.githubusercontent.com/48438852/228137237-a1b6a9ca-9b01-44ea-b043-a3d931486d16.png)
      
      ![image](https://user-images.githubusercontent.com/48438852/228137526-b22a043b-3f43-497d-98ed-dc2b3536d790.png)
      
      now save.
      
      Like this you can create many rooms where users can join and chat.
      
  11. Now go to "http://127.0.0.1:8000/"
  12. if already logged in then logout and relogin by providing either with admin or normal user credential.
  13. now you can see all available rooms where you can join and chat.

      

