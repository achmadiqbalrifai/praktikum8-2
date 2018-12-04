# praktikum8

latihan 1 (fungsi fibonacci dengan cara iteratif)

```
1.mulai program
2.int iteratif (int suku, int a, int b, int c)
3.a=0, b=1;
4.if (suku == 1) return b;
5.if (suku == 0) return a;
6.else
7.for(int i=2; i<=suku; i++){
8.c = a + b;
9.a = b;
10.b = c;
11.int suku, a, b,c;
12.cout<<"Masukkan nilai suku ke-: ";
13.cin>>suku;
14.cout<<"\nBilangan fibonaccinya untuk "<<suku<<" adalah ";
15.cout<< iteratif ( suku,  a,  b,  c);
16.selesai

```

Hasil Sreenshot 

![untitled](https://user-images.githubusercontent.com/44091204/49414418-eb0d9300-f7a5-11e8-8d65-14ba457279e9.jpg)


latihan 2

```
1.mulai program
2.faktorial dengan rekursif
3.int faktorial(int n){
4.if (n==0 || n==1){
5.cout << "1\n";
6.return 1;
7.} else 
8.cout << n << "*";
9.return n * faktorial (n-1);
10.int main()
11.int n;
12.cout << "\nMasukkan nilai n! ";
13.cin >> n;
14.cout << n << "! = ";
15.cout << "Maka nilai " << n << " faktorial dengan rekursif: " << faktorial(n) << endl << endl;
16.selesai

```

Hasil Sreenshot

![sslatihan2](https://user-images.githubusercontent.com/44091204/49414717-f614f300-f7a6-11e8-8431-e0bb0de468a1.jpg)


latihan 3

```
1.mulai program
2.int kali1(int a, int b){
3.int hasil =0;
4.for(int i=0;i<b;i++){
5.hasil=hasil+a;
 }
6.return hasil;
 }
7.int kali2(int a, int b){
8.if(b==0)
9.return 1;
10.else if(b==1)
11.return a;
12.else
13.return a+kali2(a,b-1);
 }
14.int main(int argc, char *argv[])
 {
15.int a,b;
16.cout<<"masukkan a :";
17.cin>>a;
18.cout<<"masukkan b :";
19.cin>>b;
20.cout<<"secara ITERATIF :"<<endl;
21.cout<<kali1(a,b)<<endl;
22.cout<<"secara REKURSIF"<<endl;
23.cout<<kali2(a,b)<<endl;
24.system("PAUSE");
25.return EXIT_SUCCESS;
 }
26.selesai

```

Hasil Sreenshot


![sslatihan3](https://user-images.githubusercontent.com/44091204/49415258-b949fb80-f7a8-11e8-9a50-4e2c3ef7cc64.jpg)