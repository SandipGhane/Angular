# Angular
- Angular is a js framework which allows you to create reactive Single-Page-Application.(SPAs)

# Understanding Angular-versioning
- Angular JS(angular-1) angular-1 completely Re-write in Angular-2
- Angular-3 was completely skipped.
- Angular-4,5,...,9 and so on(Every 6 month new version released.
- in Angular-9 (small incremental,backword-compatible changes).

# Project Setup
- install angular CLI(make sure first install node in your device)
- npm install -g @angular/cli@latest (install latest cli v globally in ur device).
- ng new project-folder-name

# Creating Component
- we can add component as manually(creating templete,stylesheet,classfile) / we can simplly used cli commands
- compoent structure as bellow(make sure use folder and component relivent naming conventions)
    - class file (typescript)
    - template file(html)
    - stylesheet(css/scss)
    - spec file

- we can also used following cli commands
    - ng new component component-name

# more about component (ts file)
- Component Decorator (imports from angular/core)
- used to store metadata for the related component
    @Component({
        selector:'app-root'         //it is html tag basically used in other component
        templateUrl:'./app.component.html'              //template(html) url
    })