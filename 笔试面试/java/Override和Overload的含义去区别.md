## 1.Override 特点   

1. 覆盖的方法的标志必须要和被覆盖的方法的标志完全匹配，才能达到覆盖的效果；   
2. 覆盖的方法的返回值必须和被覆盖的方法的返回一致；   
3. 覆盖的方法所抛出的异常必须和被覆盖方法的所抛出的异常一致，或者是其子类； 
4. 方法被定义为final不能被重写。  
5. 对于继承来说，如果某一方法在父类中是访问权限是private，那么就不能在子类对其进行重写覆盖，如果定义的话，也只是定义了一个新方法，而不会达到重写覆盖的效果。（通常存在于父类和子类之间。） 

## 2.Overload 特点   

1. 在使用重载时只能通过不同的参数样式。例如，不同的参数类型，不同的参数个数，不同的参数顺序（当然，同一方法内的几个参数类型必须不一样，例如可以是fun(int, float)， 但是不能为fun(int, int)）；   
2. 不能通过访问权限、返回类型、抛出的异常进行重载；   
3. 方法的异常类型和数目不会对重载造成影响；   
4. 重载事件通常发生在同一个类中，不同方法之间的现象。 
5. 存在于同一类中，但是只有虚方法和抽象方法才能被覆写。 