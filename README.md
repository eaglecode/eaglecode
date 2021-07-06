Hey there my nickname is Aquiso. I love hacking, reserve engineering, operational security and coding.
<img align ="right" src = "https://raw.githubusercontent.com/pratik-kale20/pratik-kale20/main/linux.png" width="250" height="250">

```c
/* 
 * Name: main.c
 * Author: aquiso
 * Purpose: Main /src file
 */
#include  <stdio.h>
#include  <string.h>

#define    MAX_CHARS 300

struct person {
  char nickname[MAX_CHARS];
  char hobby[MAX_CHARS];
  char nationality[MAX_CHARS];
  // contact
  char jabber[MAX_CHARS];
  char discord[MAX_CHARS]; 
};

int main(void) {
  struct person aquiso;

  strcpy(aquiso.nickname, "aquiso");
  strcpy(aquiso.hobby, "Coding");
  strcpy(aquiso.nationality, "Russian");
  strcpy(aquiso.jabber, "388888@jabber.ru");
  strcpy(aquiso.discord,"master#0001"); // a is cyrillic.

  printf("Nickname: %s\nHobby: %s\nNationality: %s\nJabber: %s\nDiscord: %s", aquiso.nickname, aquiso.hobby, aquiso.nationality, aquiso.jabber, aquiso.discord);
  return 0;
}
```
![Github stats](https://github-readme-stats.vercel.app/api?username=aquiso&show_icons=true&hide_border=true&icon_color=ffffff&bg_color=0000FF&title_color=fff&text_color=fff)
## Show ❤️ By Starring My Repos!
