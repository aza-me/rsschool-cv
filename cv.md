# Curriculum Vitae (CV) - Azizbek Savkimov

<a href="https://t.me/a_savk1mov"><img src="https://img.icons8.com/color/512/telegram-app--v1.png" width="40" height="40" /></a>
<a href="https://instagram.com/a_savk1mov"><img src="https://img.icons8.com/color/512/instagram-new.png" width="40" height="40" /></a>
<a href="https://www.linkedin.com/in/azizbeksavkimov/"><img src="https://img.icons8.com/color/512/linkedin-circled.png" width="40" height="40" /></a>

#

### About: Hi there! I'm frontend developer from Tashkent. I've some experience in the field. I'm interested in backend also, in the future i'm gonna work as backend or fullstack developer.

#

## Skills

### <b>Frontend</b>: JS, TS, React.js, Next.js, Redux, SASS, Webpack

### <b>Tools</b>: VSCode, Github-Desktop, Postman, Jira

#

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=aza-me&hide=smarty,java,actionscript&hide_border=true&theme=vision-friendly-dark&langs_count=4)](https://github.com/anuraghazra/github-readme-stats)

#

```cpp
/* Write a function searchIndex(int*, int,int) which receives an integer array, size, and value to search and returns the index of the searched element, if not found, return -1. In main, take user input for value to search, n - the array size and elements of the array. Print the index of searched value with endl. In function, do not use arr[i]; use a pointer instead. */

#include <iostream>
using namespace std;

int searchIndex(const int* array, int size, int value) {
    int index = -1;

    for (int i = 0; i < size; i++) {
        if (*(array + i) == value) {
            index = i;
            break;
        }
    }

    return index;
}

int main () {
    int value, size;
    cin >> value;
    cin >> size;

    int array[size];

    for (int i = 0; i < size; i++) {
        cin >> *(array + i);
    }

    cout << searchIndex(array, size, value) << endl;

    return 0;
}
```

#

### <a href="https://aza-breaking-bad.netlify.app/">Breaking Bad</a> (<a href="https://github.com/220879cs07/breaking-bad">code here</a>) - TS, React.js, Redux-toolkit, MUI, SASS

#

### 🎓 Student of AKFA university - (2022-2026)

### 🎒 School №209 - (2011-2022)

### 🇺🇸 English: B1-B2

#
