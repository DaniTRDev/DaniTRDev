```cpp

struct DaniTRDev
{

  const char* m_Name { "Dani" };
  std::initializer_list<const char*> m_KnownAs = 
  {
    "OsiKaSuKe", //actual
    "Mr. Metal Punch",
    "Snoopy Do Do",
    "C0D3X"
  }
  
  std::string_view m_Location { "Spain" };
  
  std::uint32_t m_Age { 18 };
  
  /*SkillName, Years in it*/
  std::map<const char*, std::uint32_t> m_Skills =
  {
    { "C++", 7                 },
    { "C", 4                   },
    { "Node.Js", 3             },
    { "HTML & CSS", 2          },
    { "Reverse engineering", 6 }
  
  }
  
}

```
