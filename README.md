# HOW DOES TAUVARES WORK?

This should be a reference on how my work is usually done, always trying to follow the best practices on software development.
Please feel free to help me with some sugestions of improvement!

## NEW APPLICATION DEVELOPMENT PROCESS

	In this document, I will suggest an order or steps to follow to create a new Application, coming from the very beginning, when an idea flourishes, until the final delivery where a system is up and running:

### 1) A new idea appears on the horizon;

Tools used for this step: Brain

### 2) The ideation process is taken, and the final product is an ideation report;

Tools used for this step: Libreoffice, Text Editor

### 3) From the ideation report, UX design takes part and a UI/UX design report is generated, including the five layers of UX design, which are:

    • Product Objectives;
    • Specification;
    • Structure;
    • Navigation Design/Wireframing;
    • Interface/Prototyping;

Tools used for this step: Libreofice (Objectives, Specification, Structure), Indesign + Adobe Suite + Axure + HTML + CSS + Bootstrap(Wireframing, Prototyping);

### 4) Using the UI/UX design report as supporting documentation, the REST API is designed, following this sequence:

    • Entities modeling/UML class diagram creation;
    • Operations under Entities modeling/UML use cases creation;
    • Database tables creation, based on the diagrams provided before;
    • REST API implementation, based on the diagrams created. This step is achieved using a REST API generator tool, like Strongloop;
    • REST API documentation, using a REST API specification format, like Swagger, for example;

Tools used for this step: UML documenting tools, MongoDB, Strongloop, Atom, VSCODE, NodeJs;

### 5) Front-end implementation, based on the prototype created on step 3, and integration with the REST API end points;

Tools used for this step: Atom, VSCODE, HTML, CSS, Bootstrap, AngularJS, Ionic Framework, Cordova and Yeoman;

### 6) Application deployment, for testing and production;

Tools used for this step: Heroku PaaS, IBM Bluemix, etc;

### 7) Upload code to github;

Tools used for this step: Atom, VSCODE, terminal, github.com.

### 8) Go to step 1;


## Practices adopted while programming

To get a good quality during the development process, I try to adhere to best practices used in software development such as:

### 1) Create applications using the npm-init-* commands
    
    • It helps to identify each app uniquely;
    • It helps to identify the authors properly;
    • It helps to identify types of licenses properly;   

### 2) Create .gitignore file using gitignore command

    • Avoid uploading unnecessary files to the github, helping users to download smaller projects 

### 3) Create README.md, LICENSE.md (and CONTRIBUTING.md) files

    • Allows the users to get easy instructions on how to get started to the project
    
### 4) Use of ESLint (Right now I prefer the airbnb style for Javascript)

    • To maintain styling uniformity in the code, helping other developers to easily understand the source code
    

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
