```cpp

struct DaniTRDev
{

  std::tring_view m_name { "Dani" };
  std::initializer_list<const char*> m_knownAs
  {
    "OsiKaSuKe", //actual
    "Mr. Metal Punch",
    "Snoopy Do Do",
    "C0D3X"
  }
  
  std::string_view m_location { "Spain" };

  /*Skill, level*/
  std::map<const char*, const char*> m_skills
  {
    { "C++", "mid"                             },
    { "C",   "mid"                             },
    { "Node.Js", "junior"                      },
    { "HTML & CSS", "junior"                   },
    { "Reverse engineering", "mid-advanced"    }
  }
  
}

```
