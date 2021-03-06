# Roadmap - Indigo.Design App Builder
## Current Iteration
- Chart component in the Toolbox (category and pie chart)
- Github integration improvements
- local network requests support

## Going down the road
- Share and preview app from Indigo.Cloud
- CSS grid layout support
- Create sample apps with a Grid and Chart
- Data binding story
    - Northwind is flattened, make it relational (actual data that can be used in master detail context)
    - Forms builder
- Master-detail – Angular tour of heroes example
- UI Parts (custom components)
- React and Web Components Code Generation

## Previous Iterations
### Iteration 9
- Added **Category Chart** to the component toolbox
- Added **Pie Chart** to the component toolbox
- **GitHub Integration**: Publish updates without rolling back user changes
- Allow data requests from **local network sources**

### Iteration 8
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
### Iteration 7
- **Copy application** to a different workspace, and include all linked resources (theme, image assets and data)
- Select new **app templates** when creating a new app
- Select **preset layouts** when creating a new view in your app

### Iteration 6 - [blog](https://www.infragistics.com/community/blogs/b/infragistics/posts/app-builder-release-with-swagger-support-and-more)
- **OpenAPI (Swagger) Support** as part of our data-binding RestAPI story.
- **On-Premise Version of App Builder** that you can install on your own server and behind your own server firewall. This instance is runnable on any infrastructure and accessible only by internal personnel

### Iteration 5
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
