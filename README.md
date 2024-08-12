```c++
#include <iostream>

class Profile {
    private:
        std::string name;
        int         age;
        std::string location;

    public:
        Profile(std::string name, int age, std::string location) {
            this->name     = name;
            this->age      = age;
            this->location = location;
        }

        void introduce() {
            std::cout << "Name:     " << name     << std::endl;
            std::cout << "Age:      " << age      << std::endl;
            std::cout << "Location: " << location << std::endl;

            std::cout << "=================================================================" << std::endl;
            std::cout << "Welcome to my profile!"                                            << std::endl;
            std::cout << "I am in the 4th semester of Computer Science."                     << std::endl;
            std::cout << "Currently learning C++ with SFML, OpenGL and Unreal Engine."       << std::endl;
            std::cout << "Also studying Japanese and currently at N5 level."                 << std::endl;
            std::cout << "=================================================================" << std::endl;
        }
};

int main()
{
    Profile profile("Thiago Ianuch", 21, "Curitiba - Brazil");

    profile.introduce();

    return 0;
}
```

<blockquote>
  <div align="center">
  <div style="display: flex; align-items: flex-start; gap: 10px;">
      <img height=185 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ThiagoIanuch&langs_count=6&theme=codeSTACKr&layout=compact" />
      <img height=185 align="center" src="https://github-readme-stats.vercel.app/api?username=ThiagoIanuch&theme=codeSTACKr&show_icons=true" />
    </div>
    <br />
    <img src="https://komarev.com/ghpvc/?username=ThiagoIanuch&label=PROFILE+VIEWS&color=orange" />
  </div>
</blockquote>
