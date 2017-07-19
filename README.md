# hello-world
first repository
public class Overloading 
{
    public int test()
    {
        System.out.println("test1");
        return 1;
    }
 
    public void test(int a){
        System.out.println("test2");
    }   
 
    //以下两个参数类型顺序不同
    public char test(int a,char s){
        System.out.println("test3");
        return 'r';
    }   
 
    public String test(String s,int a){
        System.out.println("test4");
        return "returntest4";
    }   
 
    public static void main(String[] args)
    {
        Overloading o =new Overloading();
        o.test();
        o.test(6);
        o.test(4, 'h');
        o.test("h", 7);
        
    }
}
