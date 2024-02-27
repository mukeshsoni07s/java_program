class Base{
int a;
int b;

void getdata(int x, int y){
a = x;
b = y;
}
}
class Sub extends Base{
void display(){
System.out.println(a+" "+b);
}
}
class InheritanceTest{
public static void main(String [] args){
Sub obj = new Sub();
obj.getdata(10, 20);
obj.display();
