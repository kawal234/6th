# 6th
#include<iostream>

using namespace std;


//Q1. to find the count of digits of the input
// int main(){
//     int n,count=0;
//     cout<<"Enter the number : ";
//     cin>>n;
//     while (n>0)
//     {
//         count++;
//         n=n/10;
//     }
//     cout<<count<<endl;
//     return 0;
// }


//Q2. to find the sum of the digits in the input
// int main(){
//     int n,count=0;
//     cout<<"Enter the number : ";
//     cin>>n;
//     while (n>0)
//     {
//         int lastdigit = n%10;
//         count+=lastdigit;
//         n/=10;
//     }
//     cout<<count<<endl;
//     return 0;
// }


// Q3 . reverse the digits of the number
// int main(){
//     int n;
//     cin>>n;
//     int rev=0;
//     while (n>0)
//     {
//         int lastdigi = n%10;
//         rev = rev*10+lastdigi;
//         n/=10; 
//     }
//     cout<<rev<<endl;
    
//     return 0;
// }


// Q4. find the sum of following series
// int main(){
//     int n,sum=0;
//     cin>>n;
//     for(int i=1;i<=n;i++){
//         if(i%2==0){
//             sum-=i;
//         }else{
//             sum+=i;
//         }
//     }
//     cout<<sum<<endl;
    
//     return 0;
// }


//Q5. to print the factorial of n numbers

// int main(){
//     int n,fact=1;
//     cin>>n;
//     for(int i=1;i<=n;i++){
//         fact*=i;
//         cout<<fact<<endl;
//     }
//     cout<<fact<<endl;
    
//     return 0;
// }



// Second half 
// Learning number system

// code for converting binary to decimal

// int main(){
//     int n,dec=0,i,power=1;
//     cin>>n;
//     while(n>0){
//         int lastdigit = n%10;
//         dec += lastdigit*power;
//         power*=2;
//         n/=10;
//     }
//     cout<<dec<<endl;
//     return 0;
// }

// code for converting decimal to binary

int main(){
    int n,dec=0,i,power=1;
    cin>>n;
    while(n>0){
        int paritydigit = n%2;
        dec += paritydigit*power;
        power*=10;
        n/=2;
    }
    cout<<dec<<endl;
    return 0;
}
