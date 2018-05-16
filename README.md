# Internet banking platform of a virtual (vulnerable) financial group 

## Image
![image](https://user-images.githubusercontent.com/1051726/40121067-ab937624-595b-11e8-8400-9d03417e4ad6.png)

## How to install

```
$ python manage.py migrate         # prepare DB(sqlite3)
$ python manage.py collectstatic   # prepare static document from template
$ python manage.py createsuperuser # create superuser
$ python manage.py runserver 8000  # run the server
```
If you have any troubles, see below.
* Confirm pip install django or django-debug-toolbar


## ToDo
### Application
* Login/Logout (in progress)
* Balance (in progress / Need modeling)
* Transaction
* Loan
* Account management
* API
* IR?

### Design
* Login/Logout
* Welcome Page

## Future work
* Other financial service (credit, security, etc...)
