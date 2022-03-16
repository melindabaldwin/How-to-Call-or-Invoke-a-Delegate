# How-to-Call-or-Invoke-a-Delegate
How to Call or Invoke a Delegate
class Main{
Delegate double AreaDelegateFunc(int r);  //declaring a delegate
static Double AreaOfCircleFunc(int radius){
return 3.14*radius*radius
}
static Double AreaOfSquareFunc(int side){
return side*side
}
public static void main(){
Static AreaDelegateFunc areaOfCircle= AreaOfCircleFunc; //instantiating delegate
Static AreaDelegateFunc areaOfSquare= AreaOfSquareFunc; //instantiating delegate
calculateArea(areaOfCircle) // Calling a Delegate
}
}
public static void calculateArea(AreaDelegateFunc delegateGetArea){
delegateGetArea(3);
}
