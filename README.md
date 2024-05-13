```cpp
#include <voice.hpp>

#define HAVE_A_NICE_DAY_! 0

int introduction(){
  voice.speak("
    Hello!!! 👋

    I'm Yousef Ahmed, an 19 year-old IT student. My favourite hobbies are programming 💻 and drawing 🖌️.
    I also love working on various types of projects and exploring different fields of programming like
    game-development. I love working with c/c++ but I have no problem using any other language.
  ");

  string experiences[] = {"Web-development", "Game-development", "Low-Level Hardware-development"};

  string languages[] = {"C/C++", "Python", "Java/Kotlin (Basic Knowledge)",
                        "HTML/CSS/JS", "PHP", "MySQL", "x_86 ASM (Basic Knowledge)"};

  string tools[] = {"Git/Github", "CMake"];

  string frameworksAndLibraries = {"SFML/SDL2", "React", "Laravel (Basic Knowledge)"};

  return HAVE_A_NICE_DAY_!;
}
```
