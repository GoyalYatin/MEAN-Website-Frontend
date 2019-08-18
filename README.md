# MEAN-Website-Frontend
Frontend application using Angular

Backend application is written in [MEAN-Website-Backend](https://github.com/GoyalYatin/MEAN-Website-Backend) repo.

## Index
- [Architecture](#arch)
- [Setup](#setup)
    - [Setup Angular Project](#project)
    - [Add Bootstrap and Font-awesome](#bootstrap)
- [UI View](#ui)
- [Development server](#dev)
- [Generate Build files](#build)
- [Reference](#ref)
- [License](#license)

## <a name="arch"></a>Architecture
![Highlevel](doc/highlevel.png)

Above picture describes how the applications are positioned. This is high level flow.

Testing is done manually. The tests can be automated using Robot framework's requests and ui testing libraries.

![Lowlevel](doc/lowlevel.png)

This picture describes the sequence of the calls, this is low level design for this complete application, this repo only consist of frontend side.

## <a name="setup"></a>Lets setup the environment
#### <a name="project"></a>Setup Angular Project-
- First run ```npm install -g @angular/cli``` to install the Official Angular CLI globally
- Now run ```ng new todoapp-angular --style=scss``` to generate an Angular app.
- ````cd todoapp-angular```` and then ````npm install````
- Now run ````ng serve```` and Go to http://localhost:4200 to see the generated app.

#### <a name="bootstrap"></a>Add Bootstrap and Font-awesome 
Run ````npm install --save bootstrap@4.0.0-beta @ng-bootstrap/ng-bootstrap font-awesome````


Other installations needed before running full app
````
npm install --save rxjs-compat
npm install @angular/http@latest
````

## <a name="ui"></a>UI View
![ui](doc/ui.PNG)

## <a name="dev"></a>Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## <a name="build"></a>Generate Build files
Run `ng build` to generate Built Files in the dist directory.

## <a name="ref"></a>Reference
https://medium.com/@nomanbinhussein/mean-app-tutorial-with-angular-4-part-2-4250522c845

## <a name="license"></a>License
[MIT](LICENSE) license