#Visual Studio Team Services Code Coverage Widgets#

## Release Notes
* 1.0.162
    * Displayed build name now links to build details.
* 1.0.149
    * Fixed defect where build was not showing as selected.
    * Added configuration option to display build name on widget. 
    * Updated to match native style.
* 1.0.122
    * Widget can now be resized to one or two columns in width.
* 1.0.119
    * Build definitions are now sorted alphabetically.
* 1.0.99
    * Initial release. Includes a single widget that extracts "Line" (.NET) or "Lines" (Java) code coverage results from unit tests executed during a build.

## Code Coverage Widget
This widget displays the percentage of unit test code coverage based on a selected build definition. If a build definition does not have any unit tests results recognized by the widget or if has not yet been configured, it will indicate so with a message displayed within the widget.

![](img/preview1.png)

The following configuration options are available:

![](img/screenshots/configuration.png)

* **Title** - Title of the widget as it is displayed on the dashboard.
* **Build Definition** - Choose the build definition you want code coverage displayed for on the widget.
* **Additional options**
    * **Show the name of the build** - Select if you want the name of the build to be displayed on the widget.

## Known Issues
* None.