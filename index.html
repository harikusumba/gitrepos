var app = angular.module('myApp', ['ui.router', ]);

app.config(function($stateProvider) {
  $stateProvider

  .state('home', {
    url: '/',
    templateUrl : 'home.html',
    controller  : 'HomeController'
  })

  .state('details', {
    url: '/details/:repoindex',
    templateUrl : 'details.html',
    controller  : 'DetailsController'
  })
});
app.run(function($state){
  $state.go('home');
});
app.factory('myservice', function($http){
  return $http.get('https://api.github.com/repositories');
  
});
app.controller('HomeController', function($rootScope, $scope, $http, myservice) {
  $scope.message = 'Loading Git Repos';
  
  myservice.success(function(response){
    $rootScope.showdata = response.splice(0,5);
  });
});

app.controller('DetailsController', function($scope, $stateParams) {
  $scope.message = 'Loading Repo Details';
  repoindex = $stateParams.repoindex;
  $scope.repodata = $scope.showdata[repoindex];
  
});
