# Roadmap - Ignite UI App Builder
## Current Iteration
- Pass data when using Navigation routes
- Dependent variables support
- React code generation

## Going down the road
- **App Builder SDK**
- **Embedded integration**
- **Query Builder Component**
- **Forms builder**
- **Hierarchical Grid** as part of the toolbox
- **Dock Manager** as a layout setup - design surface
- **CSS grid** layout support
- **UI Parts** (custom components)
- Pivot configurator
- New data connectors

## Previous Iterations
# Iteration 22 (Released on December, 2023)
- **Manage all variables** defined in your app from a single location. 
- Added **Financial Chart** to the component toolbox.
- Added **Value Change** interaction event for **Date Picker** component.
- Angular apps are generated using **Ignite UI for Angular `16.1.11`**.
- Added an option to **select all** endpoints when configuring an OpenAPI-based datasource.
- Bug fixes and general improvements.

# Iteration 21 (Released on October, 2023) - [Blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/master-detail-style-apps)
- **Create and edit variables** to pass data between components (local vars) or views (global vars).
- **Initialize value of array/object** variable from an API request.
- Update target variable's value using **"Set Variable"** action, when defining a user interaction (event).
- Use **"Selection changed"** or **"on Click"** events to update variables.
- **Bind component properties** to variable's value or nested data-fields for object type variables.
- **Bind component data** to API endpoints with URL params (path and query params).
- Bug fixes and general improvements.

# Iteration 20 (Released August, 2023) - [Blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/app-builder-grid-column-templates)
- Added Combo **Single Selection** feature.
- Added support for **Material Extended Icons**.
- New Stepper **navigation actions**.
- New Indigo.Design UI Kit for **Fluent 1.3**.
- NewIndigo.Design UI Kit for **Material 1.3**.
- Angular apps are generated using **Ignite UI for Angular `16.0.15`** ([Changelog](https://github.com/IgniteUI/igniteui-angular/releases/tag/16.0.15)).
- Bug fixes and general improvements.

# Iteration 19 (Released June, 2023)
- Added **Grid Column Templating** - Header, Cell display and Cell editing
- UI for browsing and navigation through schema entities in OpenAPI definition
- Toolbox components linked to relevant help documentation
- Angular apps are generated using **Ignite UI for Angular `16.0.0`** ([Changelog](https://github.com/IgniteUI/igniteui-angular/releases/tag/16.0.0))
- Travel App: improvements for the background positioning of images
- Bug fixes and general improvements.

## Iteration 18 (Released May, 2023)
- Added **Stepper** and **Reveal Dashboard** to the component toolbox.
- Added new **sample app** - Health Vault.
- Switch between **licensed vs. unlicensed packages** when generating apps.
- Improved layout heuristics to create **CSS Flexbox layouts from Figma designs** that use Auto-layout.
- Updated **Figma Material UI Kit** to **v1.3**.
- Updated **Figma plugin** to create apps using theme palette and **Dark theme**.
- Automatically extract SVG and PNG as image assets when creating apps from Figma design files.
- Unified dropdown in App menu to download design system resources and to join our Discord channel.
- Updated **sample apps** - Travel app, Team Collaboration, Ecommerce Auto Shop and HR Portal.

## Iteration 17 (Released April, 2023)
- Blazor code generation for **Combo**, **Select** and **Dialog** components.
- New toggle for unlicensed code export
- Sample application updates - Team Collaboration, Ecommerce Auto Shop
- Focus on bug fixing and general improvements
- Design System Model upgrade to 4.7.4

## Iteration 16 (Released March, 2023)
- New sample application - Health Vault
- Figma import story enhancements
- Released new version of [**Indigo.Design UI kit** for Figma](https://www.figma.com/@infragistics).
- Released new version of [Figma plugin](https://www.figma.com/community/plugin/1170035114372031474).
- Focus on bug fixing and general improvements
- Design System Model upgrade to 4.7.3

## Iteration 15 (Released February, 2023) - [Blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/app-builder-release-with-grid-crud-operations-nested-iterators-and-more)
- Configure REST API methods **POST/PUT/DELETE** when creating a datasource based on **OpenAPI** definition.
- New **Data-action** for creating, updating, and deleting records in **Grid** component.
- Use Hierarchical type data in **Tree-Grid** and **Tree** component.
- Added support for **nested data-binding** when repeating components based on hierarchical data.
- Group and aggregate data in **Category chart** when repeated labels are present.
- Added two new **sample apps** - Learning portal and Inventory management.
- Added `align-self` property to override V.align and H.align defined on parent layout (CSS Flex-box).
- Added `border-radius` property to set Rounding for Row/Column/Absolute **layout** components
- Show App name as page title in the browser
- Select all data-fields when adding a new data collection
- Added option to maximize the Create new application dialog
## Iteration 14 (Released December, 2022)
- Added **Pivot Grid component** to the component toolbox.
- Added Hierarchical data support for **Tree Grid** component.
- Added combo code generation for WC.
- Released [**Indigo.Design UI kit** for Figma](https://www.figma.com/@infragistics).
- Released [Figma plugin](https://www.figma.com/community/plugin/1170035114372031474) to create an app from designs.
- Added new **sample app** - Movie Premieres.
- Added an option to **Remember authorization details** when connecting to REST API endpoints.

## Iteration 13 (Released November, 2022)
- **WebComponents** code generation
- **Figma** design tool support 
- **New components** as part of the Toolbox
  - Tab Container 
  - Rating

### Iteration 12 (Released October, 2022) - [Blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/app-builder-release-with-web-components-code-generation-tree-grid-and-more)
- **Share and preview app** from App Builder
- Added **Tree-Grid** and **Accordion** to the component toolbox
- Define columns collection for **Grid** component, and re-arrange columns
- Added new **sample app** - HR Dashboard
- Added support for reference objects when using **OpenAPI** definition
- Added support for **Safari browser**
- **Generate app** with licensed packages if you own a subscription
- Angular apps are generated using **Ignite UI for Angular `~14.1.0`** ([Changelog](https://github.com/IgniteUI/igniteui-angular/blob/master/CHANGELOG.md#1410))
- Bug fixes

### Iteration 11 (Released August, 2022) - [Blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/app-builder-release-with-blazor-server)
- Added **Tree component** to the component toolbox, for Blazor and Angular.
- Generate your app for both **Blazor WebAssembly and Server**
- Added support for `grid-gap` in **row and column layout (Flexbox)**
- Added **filtering for endpoints** when configuring OpenAPI datasource
- Generate **Expansion panel** as a Blazor component.
- **UI Kits** support dedicated content area inside **Tab Layout**
- Repositioned zoom settings for design surface to app toolbar
- Navigation Drawer now has a droppable area and you can add components like the Tree

### Iteration 10 (Released July, 2022)
- **Angular 14** upgrade
- Exposing all available **google fonts** in the theme editor
- Improvements in the Angular/Blazor **code generation**

### Iteration 9 (Released June, 2022) - [Blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/app-builder-release-with-charts-support)
- Added **Category Chart** to the component toolbox
- Added **Pie Chart** to the component toolbox
- **GitHub Integration**: Publish updates without rolling back user changes
- Allow data requests from **local network sources**

### Iteration 8 (Released May, 2022)
- Create designs in Sketch with **four new UI kit(s)** matching Material, Fluent, Bootstrap and Indigo theme.
- **Dark theme** support for **Blazor**
- Generate code for **Blazor** apps:
  - Added support for more components - **DropDown, Chip, Slider, Snackbar**
  - Updated code generation for **Navigation drawer, Navigation bar, and Card**
  - Generate **click interactions** that use open/close or show/hide actions
  - Support for repeating components based on bound data (collection).
- Improved parsing for colors when importing apps from Sketch
- Improvement for both Angular and Blazor - Code output now contain **less properties with default values**
- Updated "Task Management" **sample app** with new visual styles.
- You can set appearance properties for **Navigation bar**
- **Download App builder** desktop app from main App-Menu
- 
### Iteration 7 (Released April, 2022) - [Blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/app-builder-release-with-copy-application-new-app-layouts-and-presets)
- **Copy application** to a different workspace, and include all linked resources (theme, image assets and data)
- Select new **app templates** when creating a new app
- Select **preset layouts** when creating a new view in your app

### Iteration 6 - [blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/app-builder-release-with-swagger-support-and-more)   (Released March, 2022)
- **OpenAPI (Swagger) Support** as part of our data-binding RestAPI story.
- **On-Premise Version of App Builder** that you can install on your own server and behind your own server firewall. This instance is runnable on any infrastructure and accessible only by internal personnel

### Iteration 5  (Released January, 2022)
- Sketch UI Kit Improved Theming Support - The light/dark mode toggle that changes the surface color now affects how gray colors are set up - as a derivative of black or white.
- UI Kits Version Check updates - Now matching `<major>.<minor>` for consistency between parser dll and symbol. `<patch>` will be ignored and wont throw an error if the symbol version is higher than the parser version (#13942)
- Maintenance updates and bug fixes

### Iteration 4 - [blog](https://www.infragistics.com/community/blogs/b/jason_beres/posts/app-builder-release-with-blazor-desktop-app-and-more)
- Design and generate your app for Blazor (beta)
- Install App Builder as a desktop app on Windows, macOS, and Linux
- Added Indigo.Design UI kit for Adobe XD
- Create an app from designs using our new Adobe XD plugin
- One level nested array binding support

### Iteration 3 - [blog](https://www.infragistics.com/community/blogs/b/jason_beres/posts/indigo-design-app-builder-october-release-with-assets-support) 
- Asset support and storage
- Upload Sketch file to Indigo Cloud from the Sketch plugin
- Other improvements:
  - Include REST endpoint URL in the generated app instead of hard-coded JSON data - Youtube explanation.
  - Extract images available in your Sketch file and add it to the Workspace assets library.
  - Added context menu for Document outline elements.
  - Show outermost container (View) as the root-level element in the Document outline.
  - Added tooltips explanations for Image fit and Layout position options.

### Iteration 2 - [blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/indigo-design-app-builder-september-release)
- Grid features update (e.g., Sorting, Filtering, Editing)
- New component part of the Toolbox
    - Snackbar
- Added **Quick-Tips** to learn about Flexbox layouts, and App Builder features
- Publish to Github to add a workflow to automatically build and test the project across different versions of node.

### Iteration 1 - [blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/indigo-design-app-builder-july-release)
- GitHub Integration
- New component part of the Toolbox
    - Banner
    - Slider
- New sample apps – the new Travel and E-commerce applications 
- Korean translation
- Master and child view in Preview
- Drag and Drop reorder in the document outline and design surface

### Iteration 0 (Public Preview)
- Full WYSIWYG App Design with 30+ UI Controls
- Material, Bootstrap, Fluent and Custom Themes & Typography
- Build custom themes
- UI Controls Library with Properties Editors
- Layouts with Relative, Absolute, Fixed & Sticky Positioning
- Download Complete Angular Project
- Instant App Preview & Code Preview
- Library of Sample Apps and Starters
- Import Sketch files directly to IDE and continue working 
