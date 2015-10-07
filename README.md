<a href="javascript:void(0)" ng-repeat="r in startArry" style="text-decoration:none" ng-click="setStar(r.value)">
  <i class="icon {{r.icon}}"></i>
</a>

Se puede cambiar por:

<a href="javascript:void(0)" ng-repeat="r in startArry" style="text-decoration:none">
  <i class="icon {{r.icon}}" ng-click="setStar(r.value)"></i>
</a>

solo cambia la invocación de la directiva ng-click="setStar(r.value)" dentro del tag <i></i>, solo 
habria que hacer una prueba en dispositivo fisico.
