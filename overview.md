#Visual Studio Team Services Code Coverage Widgets#

## Release Notes
* 1.0.98
    * Initial release. Includes a single widget that extracts "Line" (.NET) or "Lines" (Java) code coverage results from unit tests executed during a build.

## Code Coverage Widget
This widget displays the percentage of unit test code coverage based on a selected build definition. If a build definition does not have any unit tests results recognized by the widget or if has not yet been configured, it will indicate so with a message displayed within the widget.

![](img/preview1.png)

The following configuration options are available:

![](img/screenshots/configuration.png)

* **Name** - Name of the widget as it is displayed on the dashboard.
* **Build Definition** - Choose the build definition you want code coverage displayed for on the widget.

## Known Issues
* When returning to the configuration screen of an existing widget the previously chosen build definition does not show as selected.