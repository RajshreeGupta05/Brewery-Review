# Brewery_Review_system
 * Users can query breweries by_name, by_city, by_postal, and by_type params.
* Search autocomplete feature.
* Users can rate breweries and post reviews.
* Google maps on brewery-details page
* Caching breweries data and search results to optimize page response time.


## Screenshots

Brewery-details page:

![Brewery-details page](https://github.com/RajshreeGupta05/Brewery-Review/blob/main/Screenshots/brew_list.png)
<br>

Reviews section:
![Reviews section](https://github.com/RajshreeGupta05/Brewery-Review/blob/main/Screenshots/review.png)
<br>




Profile page:

![Profile page](https://github.com/RajshreeGupta05/Brewery-Review/blob/main/Screenshots/profile.png)
<br>

Login page:

![Log-in page](https://github.com/RajshreeGupta05/Brewery-Review/blob/main/Screenshots/login_page.png)
<br>

Sign-up page:

![Sign-up page](https://github.com/RajshreeGupta05/Brewery-Review/blob/main/Screenshots/sign_up.png)
<br>
## Configuring AWS RDS 

Adding shortly.

## Running the project locally

### Pre-requisites

* Make sure you have [Python 3](https://www.python.org/downloads/) and pip installed on your system.

### Steps

1. First, clone the repository to your local machine: 
  
   ```bash
   git clone https://github.com/RajshreeGupta05/Brewery-Review.git
   ```
  
2. Then cd into the project folder (base directory)

3. Install virtual environment and activate it:
* For Windows:
   ```bash
   pip install virtualenv
   virtualenv venv
   venv\Scripts\activate
   ```
* For Ubuntu Linux:
   ```bash
   sudo apt install virtualenv
   virtualenv -p python3 venv
   source venv/bin/activate
   ```
  
4. Install the dependencies as in `requirements.txt`:
  
   ```bash
   pip install -r requirements.txt
   ```
  
5. Edit `settings.py` inside `django_web_app` folder and run the development server:

   ```bash
   python manage.py runserver
   ```

6. Now, copy the url http://127.0.0.1:8000 and paste it in your web browser's address bar. 

### Superuser

7. To log-in as admin at http://127.0.0.1:8000/admin create a super user:

   ```bash
   python manage.py createsuperuser
   ```

