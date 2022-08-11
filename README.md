# CodeChef

You can learn about AES encryption in [here](https://www.coderstool.com/aes-encryption). I use CBC Mode Key Size 128.

```
Encoded Text:
nEys1iwq0axK6OSVTuPtGHMB6YlCtIu2VpjGEoOwzJEGFtTjCZrFss2FBIHx4f1JIoBBxY5ypCQCtotrO5NLRgWBjXW+Eu3HySDHyoo2W8QDKcih7f6IDNvxtgXH/tGiP07E5PSCnzq5dIiBkTqUyxpkjBQHQW66WROh2ehdUE6uhZ6UMBTjWpcgwHmFP1gGy0xUHsPK11vHpzJ8iwv2uhPfbV54p3k5mJ33B4BEFdxJIHvwVFHck/gP9EZaKcv5
Initial Vector (IV):
tl39skp1kg62vc6x
Secret Key:
32k34su3bcuqbz3b
```
You can use the above information to verify that you will be using AES.

If nothing unexpected happens, the code would be:
```
#include<bits/stdc++.h>
using namespace std;
int main() {
  srand(time(0));
  for(int i=1;i<=16;++i) {
    int t=rand()%36;
    if(t<10) putchar(t+'0');
    else putchar(t-10+'a');
  }
}
```
