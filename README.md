<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Osama%20Abazied-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/osama-abazied-298518305)
[![Email](https://img.shields.io/badge/Email-osamaabazied%40gmail.com-c14438?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=osamaabazied@gmail.com)

</div>

---

# Hi, ich bin Osama Abazied

Ich studiere Informatik an der Hochschule Darmstadt und interessiere mich besonders für Softwareentwicklung, objektorientierte Programmierung und den Bereich künstliche Intelligenz.  
Mein Schwerpunkt liegt auf **C++**, außerdem arbeite ich mit **C#**, **SQL**, **Python**, **Java** und **JavaScript**.

---

## 👨‍💻 About Me in C++

```cpp
#include <iostream>
#include <vector>
#include <string>

class OsamaAbazied {
public:
    std::string name = "Osama Abazied";
    std::string role = "Informatikstudent an der Hochschule Darmstadt";
    std::vector<std::string> mainSkills = {
        "C++", "C#", "SAP", "Python", "Java", "JavaScript"
    };
    std::vector<std::string> focusAreas = {
        "Objektorientierte Programmierung",
        "Algorithmen und Datenstrukturen",
        "Netzwerke",
        "Eingebettete Systeme",
        "Verteilte Systeme",
        "Künstliche Intelligenz"
    };

    void introduce() const {
        std::cout << "Hi, ich bin " << name << ".\n";
        std::cout << "Schwerpunkt: " << mainSkills[0] << std::endl;
    }
};
