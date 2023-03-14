# Blog template

---

### About project
Blog is a platform that brings together people who are passionate about various topics and are ready to share their knowledge and experience. Create a community of people who will develop and learn new things together.
This project is a simpe version for a personal blog, where you can talk about your life, ideas, projects, etc., as well as customize it using your templates (html/css/ js).

---

### Features
- Canonical URLs for models and SEO-friendly URLs for blog entries;
- Splitting objects into pages;
- Django forms so that your users can recommend email posts and comment on them;
- Generated post recommendations using complex sets of queries;
- Using custom Django template tags and filters to provide custom functionality to templates;
- A sitemap so that search engines can scan your site and RSS feed so that users can subscribe to your blog;
- A search engine for your blog using the PostgreSQL full-text search engine.

---

### Technologies
- Django
- PostgreSQL
- Markdown
- taggit

--- 

### How to install

To begin with, you should clone a repository for yourself, [create virtual env](https://docs.python.org/3/library/venv.html) and install the requirements

```bash
pip install -r requirements.txt
```
creating new models

```python
python manage.py makemigrations
```

and applying it
```python
python manage.py migrate
```

the last step to configure, you need to create a superuser
```python
python manage.py createsuperuser
```

command to run the server
```python
python manage.py runserver
```
## Have a nice day!
