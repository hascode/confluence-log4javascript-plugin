
# Confluence Log4Javascript Plugin #

---------------

## About ##

Allows you to use the log4javascript logging API in your Confluence instance.

Confluence port based on Tim Down's popular JavaScript logging framework [log4javascript].

---------------

## License ##

This plugin is distributed under the [Apache License, Version 2.0].

The logo is taken from [FreeImages.co.uk].

[![FreeImages.co.uk](http://www.freeimages.co.uk/bitmaps/freeimagesuksmall.gif)](http://www.freeimages.co.uk/)

---------------

## Download ##

Download the plugin using your Confluence's Universal Plugin Manager or download the plugin from the [Atlassian Plugin Exchange].

----------------

## Usage ##

	// 1. creates a new logger
	var log = log4javascript.getLogger();

	// 2. create an appender . we're using the PopUpAppender here
	var appender = new log4javascript.PopUpAppender();

	// 3. adds the appender to the logger
	log.addAppender(appender);

	// 4. do some logging
	log.warn("this is a warning");

----------------

## Issue Tracking ##

Please use the [issue-tracker] to report issues or feature requests.

----------------

## Contact ##

Please feel free to contact me at my website, [www.hascode.com] but for issues, please use the [issue-tracker].

-----------------

## Plugin Website ##

For additional information, please take a look at the [project's website].

-----------------

  [log4javascript]:http://log4javascript.org/
  [Apache License, Version 2.0]:http://www.apache.org/licenses/LICENSE-2.0.html
  [Atlassian Plugin Exchange]:https://plugins.atlassian.com/plugins/com.hascode.confluence.javascript-logging-plugin
  [www.hascode.com]:http://www.hascode.com
  [issue-tracker]:https://bitbucket.org/hascode/confluence-log4javascript-plugin/issues
  [FreeImages.co.uk]:http://www.freeimages.co.uk
  [project's website]:http://app.hascode.com/confluence-log4javascript-plugin/
  
