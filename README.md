```
  //Ví dụ dưới đây sẽ hiểu rõ hơn về nó
  
  #include <iostream>
  
  using namespace std;
  
  class Student
  {
      string name;
      int age;
      
      void getInformation()
      {
          cin >> name;
          cin >> age;
      }
      
      void display()
      {
          cout << "Name: " << name;
          cout << "Age: " << age;
      }
  }
  
  int main()
  {
      Student s;
      s.getInformation();
      s.display();
      return 0;
  }
```
