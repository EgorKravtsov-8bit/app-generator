`Material Kit </product/material-kit/>`__
=========================================

.. title:: Material Kit -  Open-source material-design UI Kit created by Creative-Tim 
.. meta::
    :description: Open-source UI Kit built on top of Bootstrap 5 - contains UI components and free sample pages

`Material Kit </product/material-kit/>`__ represents `Creative Tim </agency/creative-tim/>`__'s interpretation of Google's Material Design principles, crafted specifically for web applications. 
This kit goes beyond basic Material Design implementation by adding carefully curated animations, color schemes, 
and enhanced components while maintaining the core principles of material elevation, motion, and interaction.

    👉 `Material Kit Starters </product/material-kit/>`__ - Bundle provided by `App Generator </>`__ platorm

The toolkit features a carefully selected collection of fundamental elements, design blocks, and example pages that serve as building blocks for various web projects. 
**Material Kit** includes practical page templates for common needs such as basic authentication screens and profile pages, giving developers a solid foundation to build upon.

.. image:: https://github.com/user-attachments/assets/96b55233-cae7-4000-af56-4acb645b5ea1
   :alt: Material Kit - open-source dashboard template provided by Creative-Tim 

This free version provides a well-curated set of frontend components including buttons, input fields, navigation elements, and cards. 
Each component follows Material Design principles and can be customized to match project requirements, offering good flexibility despite being a free resource.

Project Architecture
--------------------

.. code-block:: bash

    material-kit/
        ├── dist/                   # Production-ready files
        ├── src/
        │   ├── assets/
        │   │   ├── css/
        │   │   │   ├── material-kit.css
        │   │   │   └── material-kit.min.css
        │   │   ├── scss/
        │   │   │   ├── material-kit/
        │   │   │   │   ├── bootstrap/
        │   │   │   │   ├── cards/
        │   │   │   │   ├── mixins/
        │   │   │   │   └── variables/
        │   │   │   └── material-kit.scss
        │   │   ├── js/
        │   │   │   ├── core/
        │   │   │   ├── plugins/
        │   │   │   └── material-kit.js
        │   │   └── img/
        │   ├── docs/
        │   └── pages/
        └── gulpfile.js    

Material Components
-------------------

Cards with Elevation
********************

Material Kit provides enhanced card components that follow Material Design elevation principles:

.. code-block:: html

    <div class="card move-on-hover">
        <div class="card-header p-0 position-relative mt-n4 mx-3 z-index-2">
            <a class="d-block blur-shadow-image">
                <img src="image.jpg" alt="img-blur-shadow" class="img-fluid shadow border-radius-lg">
            </a>
            <div class="colored-shadow" style="background-image: url(image.jpg)"></div>
        </div>
        
        <div class="card-body text-center">
            <h5 class="font-weight-normal">
                <a href="javascript:;">Material Card</a>
            </h5>
            <p class="mb-0">
                Find unique solutions for your design needs
            </p>
        </div>
    </div>    

Material Buttons
****************

.. code-block:: html

    <!-- Contained button (raised) -->
    <button class="btn bg-gradient-primary">Primary</button>

    <!-- Text button -->
    <button class="btn btn-text">Text Button</button>

    <!-- Outlined button -->
    <button class="btn btn-outline-primary">Outlined</button>

    <!-- Button with icon -->
    <button class="btn bg-gradient-primary">
        <i class="material-icons">favorite</i>
        With Icon
    </button>

    <!-- Floating action button -->
    <button class="btn btn-primary btn-fab btn-round">
        <i class="material-icons">add</i>
    </button>    

Additional Resources
--------------------

- Material Design Guidelines: material.io
- Creative Tim Documentation
- Support Forums
- GitHub Repository
- Regular Updates via npm

Material Kit significantly reduces development time by providing ready-to-use elements that follow consistent design patterns. 
The straightforward implementation allows developers to quickly move from concept to functional website, making it particularly valuable for those seeking to create professional-looking interfaces without the investment in premium solutions. 
The transition from template examples to customized implementations remains intuitive, making it an excellent starting point for various web projects.

.. include::  /_templates/components/footer-links.rst
