<!DOCTYPE html>
<!--[if lt IE 7]>      <html lang="en" ng-app="myApp" class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
<!--[if IE 7]>         <html lang="en" ng-app="myApp" class="no-js lt-ie9 lt-ie8"> <![endif]-->
<!--[if IE 8]>         <html lang="en" ng-app="myApp" class="no-js lt-ie9"> <![endif]-->
<!--[if gt IE 8]><!-->
<html lang="en" ng-app="myApp" class="no-js">
<!--<![endif]-->
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>My AngularJS App</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="app/bower_components/html5-boilerplate/dist/css/normalize.css">
    <link rel="stylesheet" href="app/bower_components/html5-boilerplate/dist/css/main.css">
    <link rel="stylesheet" href="app/app.css">
    <link rel="stylesheet" href="app/bower_components/angular-material/angular-material.css">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet" />
    <script src="app/bower_components/html5-boilerplate/dist/js/vendor/modernizr-2.8.3.min.js"></script>
</head>
<body ng-controller="AppCtrl">
    <md-toolbar class="md-hue-2">
        <div class="md-toolbar-tools">
            <md-button aria-label="Menu" class="md-icon-button">
                <md-icon class="material-icons md-dark  md-18">
                    menu
                </md-icon>
            </md-button>
            <h2>
                <span>Angular seed app: v<span app-version></span></span>
            </h2>
            <span flex></span>
            <md-nav-bar md-selected-nav-item="currentNavItem" nav-bar-aria-label="navigation links">
                <md-nav-item class="md-primary"  md-nav-href="#!/view1" name="view1">View 1</md-nav-item>
                <md-nav-item class="md-primary" md-nav-href="#!/view2" name="view2">View 2</md-nav-item>
            </md-nav-bar>
        </div>
    </md-toolbar>


    <div ng-view></div>

    <!--[if lt IE 9]>
        <p class="browsehappy">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
    <![endif]-->
    <!-- In production use:
    <script src="//ajax.googleapis.com/ajax/libs/angularjs/x.x.x/angular.min.js"></script>
    -->
    <script src="app/bower_components/angular/angular.js"></script>
    <script src="app/bower_components/angular-aria/angular-aria.js"></script>
    <script src="app/bower_components/angular-animate/angular-animate.js"></script>
    <script src="app/bower_components/angular-material/angular-material.js"></script>
    <script src="app/bower_components/angular-route/angular-route.js"></script>
    <script src="app/app.js"></script>
    <script src="app/view1/view1.js"></script>
    <script src="app/view2/view2.js"></script>
    <script src="app/components/version/version.js"></script>
    <script src="app/components/version/version-directive.js"></script>
    <script src="app/components/version/interpolate-filter.js"></script>
</body>
</html>
