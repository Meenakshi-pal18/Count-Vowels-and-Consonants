# Count-Vowels-and-Consonants
#include<iostream>
using namespace std;
int main(){
  string s="hello";
  int v=0,c=0;
  for(int i=0;i<s.length();i++){
      char ch=tolower(s[i]);
      if(ch=='a' || ch=='e'||ch=='i'||ch=='o'||ch=='u'){
          v++;
      }
      else if(ch>='a'&&ch<='z'){
          c++;
      }
  }
      cout<<"v="<<v;
      cout<<"c="<<c;
  
   return 0;
}
