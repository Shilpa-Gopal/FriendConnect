# FriendConnect

## Features ✨

- **User Registration:** Enables new users to register with the application.
- **User Login:** Allows users to log in and receive JWT tokens for secure authentication.
- **Friend Request System:**
  - **Send Friend Requests:** Users can send friend requests to other users.
  - **Rate Limiting:** Prevents abuse by limiting friend requests to a maximum of 3 per minute.
  - **Accept/Reject Friend Requests:** Users can accept or reject friend requests they receive.
  - **View Friends List:** Users can view a list of their accepted friends.
  - **Pending Friend Requests:** Users can see a list of their pending friend requests.
- **User Search:** Users can search for other users by email or username.

## Tech Stack 🛠️

- **Backend Framework:** Django
- **API Framework:** Django REST Framework
- **Authentication:** JWT (JSON Web Tokens) using `djangorestframework-simplejwt`
- **Database:** MySQL
- **Environment Management:** Virtualenv (optional but recommended)
- **Dependency Management:** pip

### Python Packages:

- Django==4.2.6
- djangorestframework==3.14.0
- djangorestframework-simplejwt==5.3.1
- mysqlclient==2.1.0



## Getting Started 🛠️

1. **Clone the Repository:**
   ```shell
   git clone https://github.com/Shilpa-Gopal/FriendConnect.git
   cd FriendConnect


2. **Create and activate a virtual environment (optional but recommended)**
   ```shell
    python -m venv venv
    source venv/bin/activate  
    On Windows, use `venv\Scripts\activate`


3. **Install project Dependencies:** 
    ```shell
    pip install -r requirements.txt
 

4. **Apply Database Migrations (Step1):** 
    ```shell
    python manage.py makemigrations

6. **Apply Database Migrations (Step2):** 
    ```shell
    python manage.py migrate

7. **Create Superuser:** 
    ```shell
    python manage.py createsuperuser
    username: admin
    password: admin   

8. **Run Development Server:** 
    ```shell
    python manage.py runserver    


## Contributing 🤝

Feel free to contribute to enhance the functionality of FriendConnect.

## License 📄
This project is licensed under the MIT License - see the [LICENSE.md] file for details.

## Acknowledgments 🙏

Special thanks to the Django community and contributors for making this project possible.

Happy coding! 😊
