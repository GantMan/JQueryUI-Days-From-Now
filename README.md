[GITHUB PAGE](http://gantman.github.com/JQueryUI-Days-From-Now/)

JQueryUI-Days-From-Now
======================

Add number of days from now display with any jQuery UI datepicker.
![Days From Now Screenshot](./JqueryUI-Days-From-Now/raw/master/dfn.PNG "Days From Now")

This horrible bloat of a hack is a modification of [The JQuery UI Timepicker Add On](https://github.com/trentrichardson/jQuery-Timepicker-Addon).
Using the aforementioned code, I modified the JQuery UI picker (theme friendly) to show the number of days from the current date.  This is useful 
in situations where a contract is mandated to exist X days from today, instead of knowing a particular date.

Eventually?
-----------
The plugin could use the following modifications:
* Clean up old Timepicker logic that is not used.
* Pass a parameter to use for date difference base, but have it default to today
* Use a text box instead of a span, so user can enter number of days and have the date automatically select
