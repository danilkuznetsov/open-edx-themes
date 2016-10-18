Themes for LMS and Studio
================================
This directory contains themes for LMS (Learning Management System) and Studio,
following directory structure should be followed for each theme.


.. code-block:: text

   themes
      |
      └─ my-theme
           ├── README.rst
           ├─── lms
           |     ├── static
           |     |      └── images
           |     |      |     └── logo.png
           |     |      |
           |     |      └── sass
           |     |            └── partials
           |     |                   └── base
           |     |                        └── _variables.scss
           |     |
           |     └── templates
           |             └── footer.html
           |             └── header.html
           └── cms
                ├── static
                |      └── images
                |      |     └── studio-logo.png
                |      |
                |      └── sass
                |            └── partials
                |                   └── _variables.scss
                |
                └── templates
                        └── login.html
