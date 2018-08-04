# Clio

Clio is a web based system for maintaining (meta-)information on software components. The software will be published at [eellak/clio](https://github.com/eellak/clio).

* **Task/Target**

1. The Flask application / server has to be setup with the associated database. Thus providing support to creation and modification of components, licenses and products.
2. The work should be modelled in such a way that the UI would be composed of tables and features such as filters could be applied on the data.
3. Setting up of LDAP authentication system for accounts and permissions.

* **Timeline**

[https://github.com/eellak/gsoc2018-clio/projects](https://github.com/eellak/gsoc2018-clio/projects)

1. *Solution Strategy to supplement the timeline :*
    * Our First Priority must be to discuss and work on the database schema.
    * Setup the flask server as the core backend and implement the finalized database schema.
    * Work upon the front end : UI will primarily be composed of tables and filters.
    * Setup LDAP authentication for accounts and permission.

2. *To summarize :*
    * **Phase 1 Evaluation** : Complete model creation, Complete create and update feature of components on the Flask server, Update the UI of the application.
    * **Phase 2 Evaluation** : Complete create and update feature of both licenses and products on the Flask server, Update the UI of the application.
    * **Final Submission** : Complete LDAP authentication, Document all work done, Submit final code.

* **Backend framework / Tools** : Python, Flask, Flask-SQLAlchemy (ORM), LDAP
* **Database** : MySQL
* **Front end tools** : HTML, CSS, JavaScript

*Note : The installation instructions can be found at [this](https://github.com/eellak/gsoc2018-clio/wiki/Installation) Wiki page.

### Google Summer of Code - 2018

**Student** : Gopalakrishan.V ([@gopuvenkat](https://github.com/gopuvenkat))

**Mentors**

* Alexios Zavras ([@zvr](https://github.com/zvr))
* Georgia Kapitsaki ([@gkapi](https://github.com/gkapi))

**Organisation** : [GFOSS - Open Technologies Alliance](https://gfoss.eu/)

### Work done

The basic implementation of the Clio project resides at [eellak/clio](https://github.com/eellak/clio) and the project is live at [http://snf-831091.vm.okeanos.grnet.gr/](http://snf-831091.vm.okeanos.grnet.gr/). Please pay a visit to the [Final Report](https://gist.github.com/gopuvenkat/d8433e5ed78a67e0b114db69ce675235).

All the commits I've sent to this project can be viewed here : Commits by [@gopuvenkat](https://github.com/eellak/clio/commits?author=gopuvenkat). To look into my weekly progress, please refer my personnel [blog](https://gopuvenkat.github.io/).

### Future Work

* Setup tests.
* Dockerize the application.
* Setup continuous integration.

## Repository Structure

Top-level directory doc at [https://github.com/eellak/gsoc2018-clio/blob/master/doc/report.md](https://github.com/eellak/gsoc2018-clio/blob/master/doc/report.md) is where the notes, progress reports, etc are maintained.

## Collaborating

For real time collaboration, we use a dedicated zulip at [http://clio.zulipchat.com](http://clio.zulipchat.com)

**A big thanks to all my mentors ([Alexios Zavras](https://github.com/zvr) and [Georgia Kapitsaki](https://github.com/gkapi)) and my admin ([Kalfakakou Gratsiella](https://github.com/GratsiellaKalf)) for helping me improve my communication and programming skills during the GSoC period. It had been  a great experience for the past 3 months working together and hope to work on this project further and see it to completion!**
