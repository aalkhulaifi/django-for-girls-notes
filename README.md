# django-for-girls-notes
Django project following the Django girls Documentation to build a Django blog application

## Notes

This is a Django 2.0 project.

1. make sure the virtual environment is activated
2. On the blog.css:
	- make sure to remove those two lines to prevent the space that shows in the header.
	`h1 a {
    color: #FCA205;
    font-family: 'Lobster';
}
body {
    padding-left: 15px;
}`
3. `pip freeze >> requirements.txt`
4. make sure the static folder and the template folder are inside the blog app
5. check the Django version and MIDDLEWARE in case of WSGI errors

