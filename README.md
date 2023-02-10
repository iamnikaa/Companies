# **README**

This is a guide to setup the development environment for the full-stack web application **Companies** built using Django and React.

## _Prerequisites_
***
* Node.js
* npm
* Python 3
* pip


## _Setting up the backend_
***
1. Clone this repository: [Companies](https://github.com/the-dark-eye/Companies.git)
```git 
git clone https://github.com/the-dark-eye/Companies.git
```
2. Navigate to the repository folder:
```bash
cd Companies
```
3. Create a virtual environment named "venv" and activate it:
```bash
python -m venv venv
cd venv/scripts
./activate
```
4. Install the required Python packages:
```bash
pip install -r requirements.txt
```
5. Navigate to the root directory of the project "Companies" and migrate the database:
```python
python manage.py migrate
```
6. Add Data from csv file to local database using custom function:
```python
python manage.py add_data
```
7. Create a superuser for the django admin interface:
```python
python manage.py createsuperuser
```
## _Setting up the frontend_
***
1. Go to the frontend directory:
```bash
cd frontend
```
2. Install the required npm packages:
```bash
npm install
```
## _Running the development server_
****
1. Navigate to the repository directory "Companies" and start the Django development server:
```python
python manage.py runserver
```
2. Start the React development server in another terminal window:
```sql
npm start
```
3. Access the application at http://localhost:3000 in your browser.



