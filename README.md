###0x00. AirBnB clone - The console
![AirBnb Logo](https://www.digital.ink/wp-content/uploads/airbnb_logo_detail.jpg)


##Welcome to the AirBnB clone project!

Before starting, please read the AirBnB concept page.
First step: Write a command interpreter to manage your AirBnB objects.

This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

    put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
    create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
    create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
    create the first abstracted storage engine of the project: File storage.
    create all unittests to validate all our classes and storage engine
##Description of the command interpreter:

The interface of the application is just like the Bash shell except that this has a limited number of accepted commands that were solely defined for the purposes of the usage of the AirBnB website.

This command line interpreter serves as the frontend of the web app where users can interact with the backend which was developed with python OOP programming.

##Some of the commands available are:

    show
    create
    update
    destroy
    count

And as part of the implementation of the command line interpreter coupled with the backend and file storage system, the folowing actions can be performed:

    Creating new objects (ex: a new User or a new Place)
    Retrieving an object from a file, a database etc…
    Doing operations on objects (count, compute stats, etc…)
    Updating attributes of an object
    Destroying an object
###Web static, what?

Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:

    Create simple HTML static pages
    Style guide
    Fake contents
    No Javascript
    No data loaded from anything

During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can’t apply any design.

Before starting, please fork or clone the repository AirBnB_clone from your partner
if you were not the owner of the previous project.
