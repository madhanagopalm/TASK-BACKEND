The backend is completely build on Django using Django Rest Framework, while the frontend is completed using ReactJS.
### Features
* Login/Registration
* Create/Edit/Delete Your Posts
* User Profile
* Comment Enable
* Admin Panel
	* Create/View/Edit/Delete A User
	* Create/View/Edit/Delete A Post By Any User
	* View/Edit/Delete All Comments In The Blog
	* View/Edit/Delete All Comments To A Specific Post
	* Publish/Unpublish A Post

## Backend Setup
1. Clone this repository: `git clone https://github.com/dojutsu-user/Django-React-Blog.git`.
2. Create a virutal environment and install all backend dependencies with pip install -r requirements.txt in your shell.
3. Run `python manage.py makemigrations`.
4. Run `python manage.py migrate`.
5. Create a superuser: `python manage.py createsuperuser`
6. Run the server: `python manage.py runserver`.
