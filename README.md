# Python Microservice Framework Testing Area
A place where I host my small project to play around with some frameworks to  test how feasible each implementation can be.

A while ago, before I knew better, I started a project on Flask and did not really fully grasp proper principles and practices of development. Years later, that project has bloated to a sorry state and I'd like to one day rectify the mistakes we did for that project and bring some order and proper structure 

## Project components
- Small, concurrent traffic
- MySQL (and MongoDB as an extension)
- ORM is possible. The idea is we do basic filtration and joins at the query level (to minimise overhead of the calculations at the python level)
- User Authentication
- Dashboard
- Graphs (optional)
- Date filtering
- Time Range filtering (Day, Month, Year, Quarter)
- Other metric filtering (ID, Username etc)

## Frameworks:
### Django
- Authentication
- URL routing
- Template engine
- Object-relational mapper (ORM)
- Database schema migrations (Django v.1.7+)

### Pyramid
- Single-file applications (can execute it via  a single .py file -- like flask)
- URL generation
- All-embracing templating and asset specifications
- Flexible authentication and authorization
- Testing, support, and comprehensive data documentation
- View predicates and many per-route views
- Function decorators
- Predicates
- Renderers

### TurboGears
- Multi-database support
- MVC-style architecture
- Support for SQLObject and SQLAlchemy
- Kid and Genshi included in preferred templating languages
- Validation with FormEncode
- Pylons as a web server
- ToscaWidgets, an application library that simplifies coordination of frontend design and server development
- PasteScript templates
- Front-facing WSGI-based servers (Paste HTTP server, CherryPy WSGI/HTTP server, etc.)
- Command-line tools
- MochiKit JavaScript library integration
- All features implemented as function decorators

### Flask
- With great power, comes great responsibility ;)
- Could just use Flask again but better with the knowledge we have now?
- Built-in development server and a fast debugger
- Integrated support for unit testing
- RESTful request dispatching
- Jinja2 templating
- Secure cookies support (client-side sessions)
- WSGI 1.0 compliance
- Unicode-based
- Ability to plug in any ORM    
- HTTP request handling

### Bottle, Cherry, Falcon
- very lightweight and flexible frameworks.. still looking into these... 

### Dash
- Really neat looking framework! 
- Looks to be specifically designed for data sciene and analytics!

[Top 11 Python Frameworks in 2018](https://stackify.com/python-frameworks/)
[Top 10 Python Web Frameworks to Learn in 2018](https://hackernoon.com/top-10-python-web-frameworks-to-learn-in-2018-b2ebab969d1a)
---

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

---
