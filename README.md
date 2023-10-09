# Segitigabolakbalik
SEGITIGA BINTANG BOLAK BALIK 

#include<iostream>
using namespace std;
int main()
{
      int n, s, i, j;
      cout << "Masukkan jumlah baris: ";
      cin >> n;

      for (i = 1; i <= n; i++)
      {
            for (s = 0; s < i; s++)
                  cout << " ";
            for (j = n; j > i-1; j--)
                  cout << "* ";
            cout << "\n";
      }
      {
            for (i = 2; i <= n; i++)
            {
                for (s = n; s > i-1; s--)
                  cout << " ";
                for (j = 0; j < i; j++)
                  cout << "* ";
                cout << "\n";
            }
      }
      return 0;
}
