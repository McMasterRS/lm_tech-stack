---
layout: default
title: Laravel vs. Symfony
parent: Backend Frameworks
nav_order: 4
---
#  Laravel vs. Symfony

When tasked with building a web application, developers often have to start by selecting the appropriate framework for the project. Laravel and Symfony are two of the most popular PHP frameworks used to develop modern websites. While these two frameworks have a lot in common, there are a number of differences that should be taken into consideration when choosing one framework over the other. In this section of the learning module, we will provide a brief comparison between these two frameworks to help developers choose the right one for their PHP project. 

## What They Have in Common

Laravel and Symfony are both open-source PHP frameworks and share many features, including:  
  
- **Object Relational Mapping (ORM):** Both frameworks provide ORM capabilities, allowing developers to interact with databases using object-oriented programming.  
- **MVC (Model–View–Controller) Architecture:** Laravel and Symfony follow the MVC architectural pattern, which helps separate the application’s concerns and improve code organization
- **Cross-Platform Support:** Both frameworks can be used on multiple platforms, including Windows, macOS, and Linux.  
- **CLI Code Generation:** Laravel and Symfony offer command-line interfaces (CLIs) that assist developers in generating code snippets, scaffolding, and performing various tasks.  
- **Multi-user Support:** Both frameworks provide features for user authentication and authorization, allowing developers to build applications with user management functionality.  
- **Internationalization Support:** Laravel and Symfony offer tools and libraries for handling internationalization and localization, making it easier to create applications that support multiple languages.  
- **Template Engines:** Both frameworks come with their own template engines (Blade for Laravel and Twig for Symfony), which simplify the process of rendering views and generating HTML output.  

## Where they differ

The main differences between Laravel and Symfony fall in one of six different categories:

- **Performance:** Most benchmarks give Laravel the upper hand when it comes to application loading speed. As a matter of fact, Laravel has an average loading time of 60 milliseconds, whereas websites built using Symfony takes more time to load with an average loading time of 250 milliseconds. Nevertheless, Symfony is known for the plethora of optimization options it provides, so skilled developers may be able to improve loading speeds if they spend enough time and effort on optimizations.  
- **Default Templating Engine:** Laravel uses Blade as its default template engine. Unlike other templating engines, Blade allows developers to use plain PHP code and create applications with zero additional overhead. Symfony uses Twig as its template engine, which offers concise and web designer-friendly templates that emphasize flexibility and security. 
- **Database Support System:** Both Laravel and Symfony use Object Relational Mapping (ORM) for data access and database support. Laravel uses Eloquent ORM. Eloquent proposes a structure where the Models are extensions of base class containing all the logic for database access. Symfony uses Doctrine ORM, which makes use of the DataMapper pattern which provides the ability to optimize database operations by queueing them instead of immediately running them.
- **Learning Curve:** Laravel often touts having a simpler learning curve compared to Symfony. Symfony may require more time and effort to learn due to its modular architecture. Laravel is also far more popular than Symfony, and as result developers may find more support from online communities and documentation when developing using Laravel. 
- **Testing:** Laravel and Symfony's testing suites are not dissimilar given that they both simulate user interactions and thus they rely on an HTTP client and a Dom Crawler. Laravel recommends the use of Feature tests (in addition to Unit tests). These tests aim to encompass large parts of the application, and are similar to Symonfy’s Application tests. However, writing a Feature test for Laravel can be easier than the equivalent Application test for Symfony, since Laravel’s TestCase class offers a simpler API.

## Wire UI

**WireUI** is a library of components and resources designed to empower web application development and is meant to be used with Laravel and Livewire. It provides a set of reusable Blade components, including form components, icons, alerts, modals, cards, data grids (PowerGrid), etc. Akin to other UI component libraries, WireUI aims to simplify the development process by offering components that are ready for production use out of the box, thus reducing the need to create components from scratch. WireUI allows developers to focus on building their web applications faster without worrying about writing code for UI components.  
  
Some key features of WireUI include:  
  
- **Blade Components**: These reusable components enhance enable faster web development by covering various aspects such as notifications, icons, form components, etc.  
- **Heroicons**: A collection of over 450 free MIT-licensed high-quality SVG icons that you can use in web projects. These icons are available as basic SVG icons and can be easily integrated into an application using WireUI.  
- **Simple Documentation**: WireUI provides simple documentation with real-life examples and detailed usage instructions. The documentation includes code examples and UI examples to help developers get started quickly.  
- **Notifications**: WireUI offers a simple and complete API for creating notifications in your application. You can use notifications to confirm actions, alert users about completed actions, or ask for confirmation before taking an action.

We conducted accessibility testing on the WireUI library to ensure that it meets modern accessibility standards and we found that the WireUI components are compatible with most screen readers and offer support for keyboard navigation and accessible focus indicators that enhance the experience for users who prefer keyboard navigation. 
