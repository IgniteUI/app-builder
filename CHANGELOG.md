# April 2022 Release
## Features
- **Copy application** to a different workspace, and include all linked resources (theme, image assets and data)
- Select new **app templates** when creating a new app
- Select **preset layouts** when creating a new view in your app

## Improvements
- Related to Swagger UI and bug fixes

## MAINTENANCE UPDATES & BUG FIXES
**Including, but not limited to:**
- Hide Swagger table context menu
- Add progress indicator for done button when adding URL
- Fix missing `requestInfo` on DS table
- Hide dropdown when there isn't baseUrl to show
- Add authorization methods required functionality
- Swagger empty file proper handling
- Prevent using empty json
- Improve performance when too many endpoints
- Select data dialog is listing the data sources instead of fields


# March 2022 Release
## Features
- **OpenAPI (Swagger) Support** as part of our data-binding RestAPI story.
- **On-Premise Version of App Builder** that you can install on your own server and behind your own server firewall. This instance is runnable on any infrastructure and accessible only by internal personnel

## Improvements
- Set image round radius using px, % or rems
- Persist zoom level of the design surface when switching between views or preview
- Improvements when generating **Blazor** apps
  - Added support for **custom themes** (color palette and typography)
  - Apply **global font** and **color/background** from the app's theme
  - Allow **custom headers** when adding REST API URL source
  - Improved code generation for **Date Picker**, **Grid** (columns), **List** and **Nav-Drawer** items
  - Added support for **nested arrays** in objects as data source

## MAINTENANCE UPDATES & BUG FIXES
**Including, but not limited to:**
- Fix the error that is thrown on "Get Assets For Sketch"
- Select component popup is cut at the top in preview mode
- On app duplication the custom viewport is lost
- Breadcrumb in data panel doesn't match the latest visual enhancements
- Icons overflow input when set fluent theme and rounding
- Detaching a tab when dragging breaks the app
- Button ir resized after editing its text
- Outline sections don't collapse when component is de-selected on canvas
- ComboBox Items are affected by preview and there's no clear button
- Select is shown in the "pick component" list when adding open/close action
- Checkbox and Switch generate label position even if set to none
- Setting dark fluent theme with roundness 1 ends up light
- Grid: Cell editing doesn't work in preview mode
- Sign out from Sketch plugin is not actually signing out
- The disabled state of buttons in the App bar doesn't work
- Assets with % or # in the name don't show in generated application
- Improve handling of Data Sources with non-ASCII Unicode names in Angular's service methods and Blazor view model
- Curly braces are not escaped in the generated text content - _Angular specific_
- Ensure app root container stretches to full height - _Blazor specific_
- Multiple iterators bound the same data should no longer create multiple data properties in the same view - _Blazor specific_


# January 2022 Release

## IMPROVEMENTS
- **Sketch UI Kit Improved Theming Support** - The light/dark mode toggle that changes the surface color now affects how gray colors are set up - as a derivative of black or white.
- **UI Kits Version Check updates** - Now matching `<major>.<minor>` for consistency between parser dll and symbol. `<patch>` will be ignored and wont throw an error if the symbol version is higher than the parser version (#13942)

## MAINTENANCE UPDATES & BUG FIXES
**Including, but not limited to:**
- Workspace title not updated
- Create new workspace cancel shows invalid state
- About dialog/Header/Account dialog improvements
- Add template for data source search empty state
- Move "View All" workspaces link out of the scrollable area
- Consider a property as bound when type is Bound and data field is set(#14296)
- Avoid data section for components with IsOverlay = true (#14305)
- Fix custom list item content #14322
- Notify visuals updates to update bounds and overlays (#14306)
- Hide parent adorner while moving or resizing (#1388)
- Limit zoom in/out actions (#14268)
- Refresh main menu on new apps notified by realtime sync (#14295)
- To work with the new way color variations are described in case a layer has fills, instead of setting style, the opacity modifies the color alpha to achieve the same color shade (#14552)
- Parsing deeply nested groups and backgrounds throws an error (#13954)
- People app parsing fix (#13905)
- Dialog window navigation did not work ([GitHub issue](https://github.com/IgniteUI/app-builder/issues/7))

# December 2021 Release
## FEATURES
- Design and generate your app for Blazor (beta)
- Install App Builder as a desktop app on Windows, macOS, and Linux
- Added Indigo.Design UI kit for Adobe XD
- Create an app from designs using our new Adobe XD plugin
## IMPROVEMENTS
- Updated the App Builder menu to manage your apps and group workspaces
- Added support for Nested collection inside a response object
- Added Export to Excel feature to Data-Grid component
- Added automatic compression when uploading large images as assets
- Sketch Plugin Updates - improved theming and "Create new app from Sketch" story

# October 2021 Release
## FEATURES
 - **Upload your images** to Assets library and share it across all apps in the same Workspace
 - **Download uploaded images** used in the app when you publish or download app source code
 - **Create app** directly from Sketch plugin
## IMPROVEMENTS
 - **Include REST endpoint URL** in the generated app instead of hard-coded JSON data
 - **Extract images** available in your Sketch file and add it to Workspace assets library
 - Added context menu for **Document outline** elements
 - Show outermost container (View) as the root-level element in the **Document outline**
 - Added tooltip explanations for **Image fit** and **Layout position** options
## MAINTENANCE UPDATES & BUG FIXES
 - General bug fixes and maintenance updates

# September 2021 Release

## FEATURES

 - Added more features to the **Grid** component part of the toolbox.
 - 10+ new features including Sorting, Filtering, Cell/Row editing, Paging, Selection, GroupBy and more.
 - Added **Snackbar** to the component toolbox.
 - Onboarding experience improvements:
  - Quick tips - The quick-tips feature aims to gradually educate users about the concepts and accelerators available. The quick-tips are triggered when the user completes a certain action in the App Builder, like resize a component or add a new child view.
  - The sample apps show new visual thumbs with descriptions.
- GitHub Actions Integration - GitHub Publish now adds a workflow doing a clean install of node dependencies, cache/restore them, build the source code and run tests across different versions of node.

## IMPROVEMENTS

 - Reduced loading time on app download an Publish to GitHub
 - "Generate app" button is now "Publish to GitHub".
 - "Create new app" Dialog is now with two sizes. One for larger displays, and one for smaller displays. New section to get assets for Sketch or XD.
 - All sample apps are with updated meaningful thumbnails representing actual screenshots and with a brief text description of the app upon hover.
 - Improved loading of theming when uploading .sketch file for app generation.
 - Adobe XD files support (will be available when the Adobe XD Plugin is ready).

## MAINTENANCE UPDATES & BUG FIXES

 - Improved load times for apps and general performance tweaks when using the app builder.
 - General bug fixes.
 - Fixed errors with data repeated elements.
 - Data source list population fix for bindable elements.

[LEARN MORE](https://www.infragistics.com/community/blogs/b/infragistics/posts/indigo-design-app-builder-september-release)


# July 2021 Release

## FEATURES

 - **GitHub integration**- Publish your generated app to an existing or new repository
 - Added **Slider** to the component toolbox
 - Added **Banner** to the component toolbox
 - Added Korean language translation for `https://cloud.indigo.design`
 
## IMPROVEMENTS

 - Ability to reorder components in the document outline or design surface using drag and drop
 - Ability to reorder Master and Child views in the **Views** tab of the toolbox
 - When previewing the app, switch between Master and Child views using a dropdown in the **Preview** toolbar
 - Updated **Radio** component to **Radio Group**
 - Updated **Tab Layout** to allow custom content inside Tab Header
 - Updated icons to represent content wrapping scenarios when using **Row**/**Column Layout**
 - Added two new sample apps in **Create new app** dialog 
 - Apps are generated using Ignite UI Angular `12.0.0` instead of `11.1.15`
 
## MAINTENANCE UPDATES & BUG FIXES

 - Improved load times for apps and general performance tweaks when using the app builder
 - General bug fixes

[LEARN MORE](https://www.infragistics.com/community/blogs/b/infragistics/posts/indigo-design-app-builder-july-release---what-s-new)
