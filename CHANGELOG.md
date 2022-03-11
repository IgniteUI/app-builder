# March 2022 Release
## Features
- **OpenAPI (Swagger) Support** as part of our data-binding RestAPI story.
- **On-Premise Version of App Builder** that you can install on your own server and behind your own server firewall. This instance is runnable on any infrastructure and accessible only by internal personnel

## Improvements
- Image round radius should be in percentage (#5312)
- Persist the view zoom ratio rather than using the default (#14214)

## MAINTENANCE UPDATES & BUG FIXES
**Including, but not limited to:**
- Clicking on Get Assets For Sketch throws error (#14681)
- Select's popup is cut at the top in preview mode (#14281)
- When Duplicate an App custom viewport is lost (#13739)
- Card delete Avatar and switch (#9565)
- Breadcrumb in data panel doesn't match the visual specs (#14652)
- Icons overflow input when set fluent theme and rounding (#14846)
- Detaching a tab when dragging breaks the app (#13352)
- Button resizes after editing its text (#14719)
- Outline sections don't collapse when component is de-selected on canvas (#12895)
- ComboBox Items are affected by preview and there's no clear button (#5856)
- Select is shown in the "pick component" list when adding open/close action (#6403)
- Checkbox and Switch generate label position even if set to none (#13775)
- Setting dark fluent theme with roundness 1 ends up light (#15361)
- Cell editing doesn't work (#14342)
- Sign out from Sketch plugin is not signing out (#14486)
- The disabled state of buttons in the App bar doesn't work (#14315)

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
