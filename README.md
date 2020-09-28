Term Body Class
===============

Term Body Class allows to add taxonomy term classes to the body element of
content pages and user account pages.

Installation
------------

Install this module using the official Backdrop CMS instructions at
https://backdropcms.org/guide/modules.
  
Configuration
-------------

- Visit the settings of a term reference field. For example, on a new Backdrop
  site, go to **Administration > Structure > Content types > Post > Manage 
  fields > Tags** (`admin/structure/types/manage/post/fields/field_tags`).
- Enable the option "Add as body class", and save the field settings. (The
  body class setting applies only to the field instance of this content type.)
  
Usage
-----------

- Add a post with a taxonomy term, e.g. `My term`. As a result, the
  class `tbc-my-term` will be added to the `body` element of the HTML.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/term_body_class/issues

Current Maintainers
-------------------

- [Olaf Grabienski](https://github.com/olafgrabienski)

Credits
-------

- Ported to Backdrop CMS by [Olaf Grabienski](https://github.com/olafgrabienski).
- Originally written for Drupal by [Somedutta Ghosh](https://www.drupal.org/u/sghosh).

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.
