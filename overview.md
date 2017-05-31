#Visual Studio Team Services Code Coverage Widgets#
## NOTE: This also works with Team Foundation Services (on-premise).

## Release Notes
* 1.0.190
    * Added support for Partially Succeeded builds.
* 1.0.189
    * Updated to latest SDK.
    * Minor updates to improve error handling.
* 1.0.171
    * Added configuration option to display up to two decimal places. Zero is the default.
    * Added broader configuration options for broader coverage measurement:
        * Blocks
        * Branch
        * Class
        * Complexity
        * Instruction
        * Line
        * Lines (this is the default)
        * Method
* 1.0.166
    * Added configuration option to measure Lines or Blocks.
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
* **Size** - Allows the widget to be resized to 1x1 or 2x1 (2 columns wide).
* **Build definition** - Choose the build definition you want code coverage displayed for on the widget.
* **Coverage measurement** - Choose a coverage measurement type. Lines is the default.
* **Decimal places to show** - Choose the number of decimal places to show. Zero is the default.
* **Additional options**
    * **Show the name of the build** - Select if you want the name of the build to be displayed on the widget.

## Known Issues
* None.
