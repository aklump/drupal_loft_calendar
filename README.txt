SUMMARY: A wrapper class so Drupal can use LoftCalendar. Very much an API.


REQUIREMENTS:
* PHP 5.3


INSTALLATION:
* Download and unzip this module into your modules directory.
* Goto Administer > Site Building > Modules and enable this module.
* Download the Loft Calendar library from
  https://github.com/aklump/loft_calendar and place in a suitable libraries
  folder, e.g. sites/all/libraries/loft_calendar where
  sites/all/libraries/loft_calendar/LoftCalendar.phpm is true.

CONFIGURATION:
* No options.


USAGE:
* Use the following code to get started
@code
  libraries_load('loft_calendar');
  $calendar = new DrupalLoftCalendar('2013-03');
  $calendar->get();
@endcode


--------------------------------------------------------
CONTACT:
In the Loft Studios
Aaron Klump - Web Developer
PO Box 29294 Bellingham, WA 98228-1294
aim: theloft101
skype: intheloftstudios

http://www.InTheLoftStudios.com
