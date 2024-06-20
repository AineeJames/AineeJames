```c
#include <aboutme.h>

const Programmer me = {
  .name = "Aiden Olsen",
  .contact = "olsenaiden33@gmail.com",
  .langs = {
    "c", "c++", "rust", 
    "python", "javascript", "typescript",
    "bash"
  },
  .skills = {"git", "mysql", "sqlite", "tableau", "aws"},
  .software = {"neovim", "kicad", "gtkwave"},
  .notable_projects = {
    (Project) {"ChatGPTerminator", "https://github.com/AineeJames/ChatGPTerminator",
      "A convenient way to interact with OpenAI's chat completion and image generation API's using your command line interface."
    },
    (Project) {"rust6502", "https://github.com/AineeJames/rust6502",
      "A 6502 simulator written in the rust programming language with the ability to run compiled 6502 asm."
    },
    (Project) {"ctest.h", "https://github.com/AineeJames/ctest.h",
      "A simple single header only c testing library."
    },
  }
};

int main(void) {
  desribe(me);
  return 0;
}

```
