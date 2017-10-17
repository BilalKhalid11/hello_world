angular
  .module('item', [])
  .controller(itemController)
;

itemController.$inject = ['$scope'];
function itemController($scope) {
  $scope.items = []; //items
  $scope.delete = function(item) {
    //deletion logic
  }
}
