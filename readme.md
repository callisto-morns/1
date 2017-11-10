

    %reload_ext literacy




![](https://user-images.githubusercontent.com/4236275/32387941-61eb6494-c09c-11e7-8e39-510689aab037.png)

# [Atlanta Jupyter User Group Meeting](https://callisto-morns.github.io/) [One](https://callisto-morns.github.io/)

## Saturday November 11, 2017 _@_ the Georgia Tech Research Institute

__Atlanta Jupyter User Group Meeting__ is a satellite event orbitting the [Project Jupyter](https://jupyter.org).  At each __Atlanta Jupyter User Group Meeting__, Jupyter beginners and veterans will join to share their works.  These events will attract designers, developers, and scientists across the southeast region crafted with Project Jupyter tools.

# Ticket Drop!

## [Purchase Tickets at Eventbrite for $5](https://www.eventbrite.com/e/callisto-morn-one-an-event-for-jupyter-users-tickets-39268778975)

> *Tickets on the day of the event are $10*

## [Submit a Talk or Demo](https://docs.google.com/forms/d/e/1FAIpQLSfY1c4y2vLE-q3VMBjOpvTi4pK5D6Q9KudNk25AsxQUjsT3eA/viewform)


## [Github](https://github.com/callisto-morns/one) 


## [Questions?](https://github.com/callisto-morns/one/issues) 

[![Gitter chat](https://badges.gitter.im/callisto-one/Lobby.png)](https://gitter.im/callisto-one/Lobby)

---

## Announcements

{% for post in site.posts %}

### [{{ post.title }}](one/{{ post.url }}) <small>{{post.date}}</small>

> {{post.description}}

{% endfor %}



---

# Developer

All build logic is contained with in the `readme.ipynb` file.  Use `nbconvert` to execute this notebook with the command below.

    !jupyter nbconvert --to markdown --config config.py readme.ipynb
    
## [Conference Website](https://tonyfast.github.io/callistory/)


This project maintains an index of notebooks on the `master` branch.  The Github Pages deployment separates out the HTML and Markdown content from the source documents.   

### [Travis Pages Deployment](https://docs.travis-ci.com/user/deployment/pages/)


    %%file config.py
    c.TemplateExporter.exclude_input=True
    c.TemplateExporter.exclude_input_prompt=True


    Overwriting config.py


    [NbConvertApp] Converting notebook about.ipynb to markdown
    [NbConvertApp] Writing 1191 bytes to about.md
    [NbConvertApp] Converting notebook announcement.ipynb to markdown
    [NbConvertApp] Writing 2276 bytes to announcement.md
    [NbConvertApp] Converting notebook contributing.ipynb to markdown
    [NbConvertApp] Writing 864 bytes to contributing.md
    [NbConvertApp] Converting notebook demonstrations.ipynb to markdown
    [NbConvertApp] Writing 3362 bytes to demonstrations.md
    [NbConvertApp] Converting notebook index.ipynb to markdown
    [NbConvertApp] Writing 9067 bytes to index.md
    [NbConvertApp] Converting notebook readme.ipynb to markdown
    [NbConvertApp] Writing 5002 bytes to readme.md
    [NbConvertApp] Converting notebook posts/2017-10-23-Adding-the-first-talks-Copy1.ipynb to markdown
    [NbConvertApp] Writing 784 bytes to _posts/2017-10-23-Adding-the-first-talks-Copy1.md
    [NbConvertApp] Converting notebook posts/2017-11-02-Atlanta-Jupyter-Users-Group.ipynb to markdown
    [NbConvertApp] Writing 451 bytes to _posts/2017-11-02-Atlanta-Jupyter-Users-Group.md
    [NbConvertApp] Converting notebook index.ipynb to html
    [NbConvertApp] Converting notebook readme.ipynb to markdown
    [NbConvertApp] Writing 4343 bytes to readme.md




# [contributing](contributing.ipynb)

[![Build Status](https://travis-ci.org/callisto-morns/one.svg?branch=master)](https://travis-ci.org/callisto-morns/one)

## [Submit questions and suggestions through the github issues](https://github.com/tonyfast/callistory/issues)

We hope that community participation can assist future organizers in producing diy technology events.

## Development

* __[readme.ipynb](readme.ipynb)__ provides instruction for external services.
* __[index.ipynb](readme.ipynb)__ the main event site.
* __[about.ipynb](about.ipynb)__ provides information about the event.  Who what where when how why.
* __[contributing.ipynb](about.ipynb)__ provides information about the event.  Who what where when how why.
* __[talks.ipynb](long.ipynb)__ provides provides long format presentations information.

# [Code of Conduct](code_of_conduct.md)




    %%file custom.css
    .output code {display: none;}


    Overwriting custom.css

