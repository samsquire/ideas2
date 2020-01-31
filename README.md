# Another One Hundred Ideas for Computing

This is a list of new ideas since [my last 100 ideas](https://github.com/samsquire/ideas). I hope you enjoy them as much as I did thinking about them and writing them down.

# 1. Digital Contracts

Contracts should be digitised so that anyone on any side of any contract can see what they are responsible for and any actions they can take within the contract. There should be a UI for interacting with the contract. If I have a contract with a company to do with my private data, I should be able to request data through the UI. Or if If I have a phone contract and I am eligible for an upgrade, I should be able to upgrade through the UI.

# 2. Mobile legal business creation and Personal ERP

Someone with a phone should be able to just create a business that satisfies all reporting requirements and is a legal entity. I want to see a mobile phone app that implements enterprise resource planning for the gig economy.

# 3. Telework

Computational problems can be rendered into labelled graphical video streams upon which people vote. People can solve computational problems with a television monitor, numbered graphs and a keypad that they enter sequences of numbers into. Problems like efficient scheduling of cars for carpooling or deliveries are solvable by human beings quickly with a user interface that allows one to lasso points on the map and add cars. This is for problems that are not strictly numerical.

# 4. Paper Work Language

We need a way to define work. All work can be represented digitally. This standard is that a piece of work must fit on an A4 piece of paper. A bit like a job description but each page represents a task. So you have a piece of A4 paper describing one piece of work to do. Each piece of work can depend on other pieces of work. Can be integrated into a continuous integration pipeline for human beings. Work appears in your work inbox.

Existing:

* BPMN Business Processs Modelling Notation
* JBPMN

# 5. Open Demand Mapping and Want marketplaces

People can insert demands for products and services into a demand marketplace within a geographical location. I want a dentist within 5 minutes walk of my home. I want a supermarket within 5 minutes walk of my home. In aggregate, people create demands on their local areas.

# 6. Lifestyle subscriptions

There's a single app for following any dream or any lifestyle with user created content. You pay money per month for some thing you want to do, maybe a lifestyle of healthy eating, niche hobby, sports or gym. Maybe you want to become a musician or you want a lifestyle where you live in suburbs. The company sends you recommended decisions to make, materials and gear that you need for your level of subscription. So if you said you want a lifestyle where you can get to work within 25 minutes, the app would tell you where to move to. Or if you want to eat out once a month, you can because your level of subscription includes it.

https://lifestyle-subscriptions.com

# 7. Human Query Engine

A filled inbox of questions to answer and questions generated based on my answers to previous questions. Uses random lists of words to ask interesting questions such as "Is **thingA** better than **thingB**" or "Is **thingA** meaningful with **thingB**?" or "How much money do you have in your bank account?". The data collected could be used to implement [life engine](https://github.com/samsquire/ideas#5-life-engine).

# 8. Active Slides

It should be possible to make decisions in a company via presentation software if slides accurately represent processes of the company and through data collection within the presentation software. Presentation software becomes an interactive system. I imagine anybody can connect to the presentation software via mobile device by Wifi. I imagine presentations depictions of models (flow diagrams) and frameworks (smartart) could be executable by a workflow engines. So how companies say they are going to run, is actually how they run. There could be an app store of integrations with presentations for showing information that is up-to-date and live; such as pulling in sales data from internal systems.

# 9. Scheduled Society and Virtual Placements

Human suffering could be eliminated if everyone had a virtual placement assigned. Everyone can have what they need and want if every other thing is at the right place at the right time. Place is virtual. There are virtual places such as receive X amount of Y food at Z, shop at X, sleep at X, be at X, receive X, go to X, take A to B, Complete X amount of Y work. Do Y at X time. Everyone has a set of places at any given time. Not everyone needs a virtual place at all times. If virtual places are scheduled, traffic, commuting, waiting can be eliminated. Placement is representation of a position to take in the world - it could be a place in a queue. Everyone can buy and sell placements and schedules. Basically every thing is a market and it can be financialised.

# 10. Library Mesh

Depending on a library could also involve pinging the libraries' software infrastructure so that whenever the library is changed, the dependents are also rebuilt. This would catch code that causes downstream changes to APIs. API changes are expensive.

# 11. Additive GUIs

Represent the commands that generate GUIs as a monotonically increasing set of statements about the GUI and declaratively render a GUI based on propositions of widgets in relationship to one another. Has the property of being able to extend existing GUIs by simply making more statements. See http://github.com/samsquire/additive-guis Imagine if a set of tweets could render a GUI.

# 12. Recommended music for webpage

Wouldn't it be nice if you could recommend a song to play with a web page as background music. Perhaps a meta tag with a URL to a YouTube video.

# 13. GUIs are queries

The entire GUI could be generatable as response to a query.

# 14. User URLs

As the user mouses around the GUI, a URL should be generated which is a representation of what the user is doing at any point in time including all context from the user's perspective. This is like a very deep link into an application, as the user is a resource. See https://github.com/samsquire/user-urls

# 15. Free flowing work app

Replace job interviews at individual companies with interviews with an app company to vet people for a certain kind of role. People can look at shop exterior and see a logo of an Accreditation  company and work there if they have been vetted by the app. Transport can be branded by Accreditation company and accreditation app companies can specialise in the quality of the people they hire.

# 16. Cloud accelerated desktops

Desktop computers could be accelerated by doing things remotely. If a user's filesystem is mirrored elsewhere, it can be searched remotely and results served locally without incurring any performance penalty locally. See https://github.com/samsquire/cloud-desktop

# 17. Data Bento Box

An app that downloads data from various sources online to fill 1 gigabyte of data (reddit, blog posts, articles, free books), implements a viewer and always gives you something to read while you're offline.

# 18. CMS for building webapps

A CMS for webapps: create serverside and clientside routes, register handlers from a GUI, create facts about the GUI.

# 19. Stack-upon

The OSI model makes a whole deal of sense, one layer adds promises on-top of the layers below to create an emergent complexity. Each layer makes promises to other layers. What if we had a visualization of a multi layered spreadsheet whereby each layer is a layer of the architecture of the software. Each layer is like a line in your stacktrace at the same abstraction level. In addition to formula cells representing computation, we have references that represent communication between different labelled cells. Passing data between layers is an interface which either takes you to a layer above or below to where you are at. This is where enterprise service bus mapping screens would come in handy.

# 20. Credit cards to tap into buildings

Credit cards can be used to access buildings.

# 21. Breakless Software - Depending on Promises

Churn is painful in software development. Things change without warning and things no longer compile or work together. I would like to see a more mature strategy to breaking changes and how they ripple through a software ecosystem. Software change is not cheap. Python 2 to Python 3 is some thing I'd like to avoid going forward. I want to depend on some thing that shouldn't break, that means depending on an abstraction or an interface but is depending on some thing much larger than a single interface in code. I call this depending on a promise. The interface I depend on should not break between major releases, it's stable and it's locked into the software. Javascript in the browser keeps working but my NodeJS, Ruby and Java projects break all the time due to refactoring being done on underlying dependencies. Developers need accurate statistics of code coverage of who is using what. They also need to know if they've broken some thing downstream with their changes.

# 22. Install across

Modern systems such as Elasticsearch, Consul require clusters of computers to install against. What we need is installers that can be configured to install across multiple machines, not just independent machines.

# 23. Output text as a changeable interface

Have you ever been looking at the output of a command and wanted to change the output of the command directly? Perhaps it's Kubernetes output.

You click on a piece of output text, it pops up in an editor and you change it. You then are told what you need to run to make the changed output a reality.

# 24. Programming Language designed for machine refactoring - Refactoring equivalencies

Could a programming language be designed for refactoring simplicity? Java does really well as being a language that supports automated refactorings. I want software breakage caused by refactoring to end. Perhaps the author of a refactoring of a broken signature change could provide an equivalent piece of code that acts as a bridge between the old way of doing a thing and the new way of doing the thing. This way people who upgrade can acquire the code that does the bridge and there is no software breakage.

# 25. Nested Validating YAML Editor

Deeply nested YAML is hard to edit because you do not know what context you're in. If you're modifying Kuberentes YAML, it's hard to know what is valid where. If you indent a block to the left you make the document invalid. Nested YAML editors stop you from indenting to the left by accident. Validating means that the editor tries to deserialize the YAML into the data structure used by the program and shows you that program's interpretation of the input YAML to tell you it's valid or not.

# 26. Web Form field backup

Every thing typed into a web browser should be saved in a new document that is indexed by website. This way we can have an archive of our contributions to any website. With browser synchronization, no data should slip through the cracks. We don't have to worry if a site doesn't permit a backup of our data.

Existing:

 * Lazarus Form Recovery (defunct)
 * Textarea cache
 
 # 27. Call site refactorer
 
 In a system with multiple microservices and use of shared libraries, it is difficult to carry out refactorings across codebases. The call site refactorer is a system that allows refactoring across code bases. It accomplishes this by identifying all uses of a particular signature and then showing every call site in a list. For this to work, automated refactorings must occur against the call site signature. Automated refactorings such as extract variable should work on every call site simultaneously, a bit like multiple cursor support in text editors.
 
# 28. Realistic Runnable Example Driven Documentation (RREDD)

All libraries and systems should be documented by examples. Examples that include import statements, filenames and any other basic precursor knowledge that should be known to run the example to be included so that anybody can run with it. I would argue that Flask and other simple libraries are so successful because they have a simple easy-to-run minimalist example on their home pages.

# 29. Mobile Applications download SQLite databases

Have a lot of data to transfer to a mobile client to create a useful interface? Just send an sqlite database over the wire to seed the client. Then stream updates over HTTP.

# 30. Plain text CRUD

I want an editor that looks like the Github issue editor but renders to plain text - in the format of this idea document and accepts this document as input. So I can click New Idea and have it render to this plain text markdown format.

# 31. Social desktop

I'd like my desktop environment to be social and I can search for ways of doing things, such a search for "track spending" and then I am introduced to someone's technical solution to this problem which is to show forms that collect spend amounts. If I don't like this approach, I can try another one. The line between software installation and use of someone's software is blurred.

# 32. Community Idea: Does Right & Does Wrong

Ever thought a piece of software did something right? There's no central collection of patterns that are of software done right. I would like to see a website which collects each piece of software's installation process and says what is right about it. Installation process is just an example. There's other things that we can discuss who does something right or wrong.

# 33. Chat bots that ask you randomly generated questions

Like a chat bot that messages you instead of you messaging it. As part of the Human Query Engine.

# 34. Keylogger for personal data collection

Run a key logger that logs data entered into every program on a computer to keep a record of personal data.

# 35. Chat development environment

Spin up Docker containers from a chat room. Write SQL. Write JSX React components in chat. Write reduct actions in the chat room. Everyone runs the same code and anyone can make a change anywhere. Without touching a text editor.

# 36. Wiki Problem System

A wiki that is pointed at a kubernetes or docker swarm environment with pages for various kinds of software. I can simply begin using different kinds of software that I can find via the wiki without an active deployment step. I can surf into some software. The distributed computing page provides implementations and various interfaces for distributed computing that I can use. I can write code that depends on a problem page. Each page is like an API.

# 37. Secrets-login and secrets-logout

Store your unavoidable file based secrets in /home/${USER}/secrets and have a shell script called secrets-logout that uses tar and GPG to encrypt your file based secrets when you go home. In the morning, log in with secrets-login to reverse the process.

# 38. Randomly generate your usernames for security

Do not use your name or your personal email address for logging into websites.  Your username is 50% of what's needed to get into your account. Instead, generate a new email alias and use that to login, such as name+1tvsdradv4@example.com.
 
# 39. Instant Ad Purchases

Promises in a digital advert can be directly purchased and appear in a special account with one click. If I see a deal for a product at a certain price, I can click purchase on it and instantly purchase the service or product. You could be driving down a motorway and see an advert for a product on a banner and instantly purchase it with a button on your car wheel. What you're purchasing is the promise specified by the advert. It could be a product at a certain price or more likely, a capability. Each purchase is itself a marketplace as it could be that you're buying from a reseller, you're buying a promise, which means any product that satisfies the promise can ultimately be provided to you.

# 40. Ticketless travel

A ticket is for saying where you're trying to go, not that you've paid. Ticketless travel is possible through credit cards loaded with digital tickets and NFC.

# 41. Conveyor belt GUI - Development with a chat bot

Imagine if a web request response had to be constructed by a human being. The incoming request sits on a queue. The UI has conveyor belts that take relevant information to the human operator. The human operator interacts with these request objects and constructs a response object and puts it in the response conveyor belt hole.

# 42. Depend on language feature

A programming language whereby you import language features to depend upon. Python has a PEP process and Java has JSRs. You directly depend on named groups of functionality and this determines your language experience. Perhaps the fist line of the file after the shebang says what language features to enable, such as "feature1,feature2"

# 43. World splitting app

Territories can be occupied by people who believe in the same things. If enough people used an app and voted for what they wanted on the app and agreed to move towards where other people believe the same things, people could begin to get what they want. This idea is called world splitting because you divide the world in half when you agree with a policy.

# 44. General Thing Object Editor

A general purpose CRUD editor with the flexibility and power of a file explorer.

# 45. One giant JSON structure

Can the state of an organisation be ran as a giant JSON structure?

# 46. Migrationless CMS

Headless CMSes such as Strapi require expensive migrations to keep up-to-date. I'd like a CMS that promises to be compatible from early versions with minimal impact.

# 47. Single file visualized as a directory

Take a single file with special comments to delineate directories and render in an editor as a folder with multiple files.

# 48. Continuous deployment integrated into the desktop

Titlebar of running applications reflects state of the build of a compiled application that is being compiled.

# 49. Stateful workstation

When I open a number of programs, I would like this list of programs to be persisted so that I can shut down the computer and return to them again. I'd like the same for the terminal too.

Existing:

* Tmuxinator

# 50. Empty space scheduler

The ability to schedule disk space to various purposes and to schedule files to different regions of empty space. I have three hard drives I should be able to schedule disk for my virtual machines without having to resize virtual disks.

# 51. Tips should be crowdsourced

When an application wants to show a tip, it should be crowdsourced.

# 52. Digital open source organisation

Open source community could come up with an organisation that is digital and runs every thing via code.

# 53. Open source customer service application

Integrate with chatops and case management ops to offer jobs to people on mobile phones to do customer support via chat.

# 54. An IDE that guarantees buildability

An IDE that guarantees if you can open the project, you can build it reliably the way others build it. Dependencies are fetched.

# 55. Generalized API client

Like CURL but for querying APIs and handling pagination for you.

# 56. Deep GUI

Every form of information collected by a corporation to go to a GUI server whereby data forms can be monitored and centrally tested.

# 57. Stream editor

An editor for streams, such as Bash pipelines or Kafka streams. Would allow you to replay data between points in the pipeline and test each stage independently.

# 58. Desktop Advertising

What can your computer do for you? The operating system and IDE advertises features and things it can do based on what is installed.

# 59. Personal Message Bus

My computer and software I interact with raises events all the time. I'd like to be able to hook into events that are raised and add behaviour to them.

# 60. Asynchrony editor

An interface to create asynchronous tasks definitions. I'm thinking of complicated workflows in the backends of controllers whereby multiple services need to be contacted and queried and where there are complicated error handling.

# 61 Resource scheduling

Schedule SSH keys and schedule public keys to be in different locations in a network. Schedule files to be present on certain servers.






