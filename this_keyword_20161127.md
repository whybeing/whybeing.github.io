#this keyword   this关键字(代表本类的对象);
###2016-11-27
> Within an instance method or a constructor, this is a reference to the current object — the object whose method or constructor is being called. You can refer to any member of the current object from within an instance method or a constructor by using this.

> A class contains constructors that are invoked to create objects from the class blueprint. Constructor declarations look like method declarations—except that they use the name of the class and have no return type. For example, Bicycle has one constructor:

> public Bicycle(int startCadence, int startSpeed, int startGear) {

>     gear = startGear;

>     cadence = startCadence;

>     speed = startSpeed;

> }

> To create a new Bicycle object called myBike, a constructor is called by the new operator:

> Bicycle myBike = new Bicycle(30, 0, 8);

## 封装 --> 封装private --> 构造函数(constructor,用于初始化对象，比如人一般出生就有名字，产品出厂就有SKU，售价 ) --> this关键字(代表本类的对象);
constructor函数名 = 类名；2，不用定义返回值类型； 3，不可以写return语句；   

多个构造函数是以重载形式出现的； f(x) f(x,y) f(x,y,z), ...;

constructor函数名(参数) {fields}   //语句/statements以大括号“}"或者分号";"结尾；


模糊点：参数，什么时候要写，什么时候不写；构造函数需要写，一般方法可以不用写参数?
或者说参数的传递，类/对象的通信；
