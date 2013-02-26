Welcome :)
=========

.. in beta (so be nice) ..

**Another Static Site Generator?** That’s right. Even with all the options out there, I could not find one to meet my needs. So I concocted my own *Brew*, using Flask, Flask-FlatPages, and Frozen-Flask. In six simple steps you can create a static site that generates HTML files from Markdown - which can be hosted on any web server.

Project Structure
---------------

    Brew/
        app.py
        pages/
            helloworld.md
        static/
            styles.css
        templates/
            _list.html
            base.html
            index.html
            page.html
            tag.html

Install
-------

1. Install [Git](http://git-scm.com/downloads), [Python](http://install.python-guide.org/), [virtualenv](http://install.python-guide.org/), and [pip](http://install.python-guide.org/) - if you don't already have them, of course
3. Clone this repo: 

            $ git clone git://github.com/mjhea0/brew.git
            $ cd brew

3. Create and activate a virtualenv:
    
    Unix:

            $ virtualenv venv --no-site-packages
            $ source venv/bin/activate

    Windows:  

            $ virtualenv venv --no-site-packages
            $ venv\scripts\activate
        
4. Install requirements:
        
            $ pip install -r requirements.txt

5. Create your static site:

            $ python app.py build

6. Upload the contents of the build folder to your web host of choice. That's it!

What's next?
-----------

1. Update the templates.
1. Add more Markdown files to the pages directory.
1. Update metatags on the Markdown files.
1. Finish developing your site.
1. Create your build again: `python app.py build`
1. Upload, and enjoy.

Learn More
---------

1. [Flask Documentation](http://flask.pocoo.org/docs/)
2. [Flask Extensions](http://flask.pocoo.org/extensions/)
1. [Real Python for the Web](http://www.realpythonfortheweb.com) :)

