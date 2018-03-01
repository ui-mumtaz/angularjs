Angularjs : Tracking a Form Validity

$pristine : true when the form (or any of its input) has not been touched

$dirty : the reverse of $pristine, true when the user have touched the form

$valid : true when all the form fields are valid

$invalid : true when the form (or any of its input) are invalid

DEPENDENCY INJECTION
-----------------------
IMPLICIT => controller ("abcCtrl, function ($scope, $http){})
INLINE ANNOTATION => controller ("abcCtrl, [$scope, $http, function (u,t){}])
INJECT ANNOTATION => function myCtrlFn (u,t){};
myCtrlFn.$inject = [$scope, $http];


