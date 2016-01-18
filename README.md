XIS-Mobile
==========

XIS-Mobile was designed/developed originally in the context of a Master's (MSc) Thesis project which intends to develop mobile applications using a Model-Driven Software Development approach with the goal of tackling the complexity of software development and the fragmentation of mobile platforms.  
	In order to accomplish this goal, it proposes a Domain Specific Language (DSL) to describe mobile applications in a platform-independent way and a [Sparx Systems Enterprise Architect Model Driven Generation (MDG) Technologies](http://www.sparxsystems.com/enterprise_architect_user_guide/9.3/standard_uml_models/mdgtechnologies.html) and [EMF](http://www.eclipse.org/modeling/emf)-based framework which supports the language.  
The XIS-Mobile language reuses some of the best concepts used in the XIS UML profile, used for modeling interactive systems, and introduces new ones in order to be more appropriate to mobile applications design. The latest version of the XIS-Mobile language comprises six views:

- **Domain View -** Describes the domain entities relevant to the problem domain, their attributes and the relationships among them;
- **BusinessEntities View -** Describes higher-level entities that provide context to a certain use case and interaction spaces;
- **UseCases View -** Describes the operations a user can perform in the context of a business entity and/or an external service;
- **InteractionSpace View -** Describes each application's screen, known as interaction space, namely the UI layout, the events a certain UI component can trigger and the gestures that can be performed;
- **NavigationSpace View -** Describes the navigation flow between the several interaction spaces with which the user interacts;
- **Architectural View -** Describes the interactions between the mobile application and other external entities (such as, internal providers, mobile apps or remote servers);

The XIS-Mobile Framework aims to:

1. Allow the specification of mobile applications using XIS-Mobile language through a visual editor;
2. Check the quality of the produced model;
3. Generate User-Interfaces views from the other views;
4. Generate source code from it for different platforms (Android, Windows Phone and iOS).

To accomplish these goals are being developed four modules:

1. Visual Editor based on [Sparxs Systems Enterprise Architect (EA)](http://www.sparxsystems.com.au/products/ea);
2. Model Validator using  [EA Validation API](http://www.sparxsystems.com/enterprise_architect_user_guide/10/automation_and_scripting/model_validation_example.html);
3. Model Generator based on [EA Model Driven Generation (MDG) Technologies](http://www.sparxsystems.com/enterprise_architect_user_guide/9.2/standard_uml_models/mdgtechnologies.html);
4. Code Generator based on [Acceleo](http://www.eclipse.org/acceleo) which allows model-to-text transformations with the guidance of code templates.

**Papers published in this scope:**

André Ribeiro, Alberto Rodrigues da Silva, [Evaluation of XIS-Mobile, a Domain Specific Language for Mobile Application Development], in Journal of Software Engineering and Applications, 7(11), October 2014, Scientific Research Publishing. http://www.scirp.org/journal/PaperInformation.aspx?paperID=50620. 

André Ribeiro, Alberto Rodrigues da Silva, [XIS-Mobile: A DSL for Mobile Applications], in Proceedings of ACM SAC’2014 Conference, 2014, ACM. http://isg.inesc-id.pt/alb/static/papers/2014/c120-ar-SAC-2014.pdf.  

André Ribeiro, Alberto Rodrigues da Silva, [Survey on Cross-Platforms and Languages for Mobile Apps], in Proceedings of QUATIC’2012 Conference, 2012, IEEE Computer Society. http://isg.inesc-id.pt/alb/static/papers/2012/C111-ar-quatic-2012.pdf. 

Alberto Rodrigues da Silva, João Saraiva, Rui Silva, Carlos Martins, [XIS – UML Profile for eXtreme Modeling Interactive Systems], in Proceedings of the 4th International Workshop on Model-based Methodologies for Pervasive and Embedded Software, 2007, IEEE Computer Society .http://isg.inesc-id.pt/alb/static/papers/2007/i68-as-XISUMLProfile-MOMPES2007.pdf. 


**© 2013-2016 André Ribeiro and Prof. Alberto Silva (Supervisor) – Instituto Superior Técnico, University of Lisbon, and INESC-ID. All rights reserved.**
