# IonicNativeSidemenu
Native side menu for Ionic Apps

Step 1: download the zip file and extract

Step 2: Load JS & CSS in project 
        ex: <script src="js/Drawer/IonicDrawer.js"></script>
            <link href="css/drawer.css" rel="stylesheet">
            
Step 3: Declare 'ionic.contrib.drawer' in app module
        ex: var app = angular.module('Demo',['ionic','ionic.contrib.drawer']);
        
Step 4: Changes in html template
        ex: <ion-side-menus>
             <ion-side-menu-content>
              <ion-nav-bar class="bar-positive-900">
                <ion-nav-back-button class="no-text" ng-hide="isVisible" ng-click="backToPreviousPage();">
                </ion-nav-back-button>
                <ion-nav-buttons side="left">
                  <button ng-show="isVisible" class="button button-icon button-clear ion-android-menu" menu-and-drawer-toggle>
                  </button>
                </ion-nav-buttons>
              </ion-nav-bar>
            
                 <ion-pane drawer-menu-content>
                  <ion-nav-view name="menuContent"></ion-nav-view>
                 </ion-pane>
            
                </ion-side-menu-content>
            
                <drawer side="left">
            
                    <ion-content>
            
                      --------------
            
                    </ion-content>
            
                </drawer>
            </ion-side-menus>
            
Step 5: That's it !!!

Enjoy the coding. :)
