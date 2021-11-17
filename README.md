class StudentCard {  
  int id;   //学籍番号  
  String name;  //氏名    
  
  StudentCard(int id, String name) {  
    System.out.println("StudentCardクラスのコンストラクタが呼び出されました");  
    this.id = id;  
    this.name = name;  
  }  
}  

public class ConstructorExample {  
  public static void main(String[] args) {  
    StudentCard a = new StudentCard(1234, "鈴木太郎");  
    
    System.out.println("aのidの値は" + a.id);  
    System.out.println("aのnameの値は" + a.name);  
    
実行結果  
StudentCardクラスのコンストラクタが呼び出されました
aのidの値は1234  
aのnameの値は鈴木太郎  
