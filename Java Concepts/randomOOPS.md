* to call another constructor form one constrcutor we use the "this" keyword


public constr2(int a)
{
  sout(a);
}
public constrcut1() {
  this(10)
}

finilisze() - method will be called when java is performing garbage collection

* inner classes can be static and outside classes cannot be static

* Singleton class
====================
Singleton class file
--------------------
public class Singleton {
   private Singleton(){

   }
   private static Singleton instance;

   public static Singleton getInstance(){
       // check weather 1 object only is created or not
       if (instance == null){
           instance = new Singleton();
       }

       return instance;
   }
}

Other file in which we are trying to create object of singleton class

public static void main(String args[]){
 Singleton obj1 = Singleton.getInstace(); /// will return object; as this is the first object
 Singleton obj2 = Singleton.getInstace();  // will not return object as already one object is crated and singleton class supports creation of only one object
}



=========================================================================================
Polymorphysm  is of 2 types
1. compiler time polymorphysm/ static poly - method overloading
2. runtime poly./ dynamic poly. ---> method overriding



====================================================================
- final method cannot be overriden and inheritence
-----------------------------------------------------------------------


Access Modifiers
![image](https://user-images.githubusercontent.com/54280958/176774339-43c1805b-ffcf-4f7b-9670-9e30687a3824.png)

protected = deafult ( i.e anywhere in the package ) + kids;
ONLY SUBCLASS CAN ACCESS THE BASE CLASS PROTECTED VALUES WHEN IT IS IN ANOTHER PACKAGE.

============================================================================
PACKAGES = USER DEF + INBUILT

IN-BUILT ARE DIVIDED AS
![image](https://user-images.githubusercontent.com/54280958/176780117-a6a6fb55-f366-4fe8-ab14-ef3a007b3dc8.png)


![image](https://user-images.githubusercontent.com/54280958/176788153-3d1ac924-2a54-4c8e-a697-676f2311322c.png)


