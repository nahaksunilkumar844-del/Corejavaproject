# Corejavaproject
import java.util.ArrayList;
class Student {
  int id;
  String name;
  int age;
  // Constructor
  Student(int id ,String name,int age) {
  this.id = id;
  this.name = name;
  this.age = age;
  }
  // Display student details 
  void display() {
  System.out.println("StudentIO : " + id);
  System.out.println("StudentName : " + name);
  System.out.println("Student Age: " + age);
  System.out.println("_ _ _ _ _ _ _ _ _ _ _ _ _ _ ");
  }
}
public class Main {
   public static void main(String[] args) {
   ArrayList<Student>Students = new ArrayList<>();
   
