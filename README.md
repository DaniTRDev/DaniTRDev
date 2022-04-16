```cpp

struct DaniTRDev
{

  std::string_view m_Name { "Dani" };
  std::initializer_list<std::string_view> m_KnownAs = 
  {
    "Mr. Metal Punch",
    "Snoopy Do Do",
    "C0D3X"
  }
  
  std::string_view m_Location { "Spain" }
  
  std::uint32_t m_Age { 17 };
  
  /*SkillName, Years in it*/
  std::map<std::string_view, std::uint32_t> m_Skills =
  {
    { "C++", 6                 },
    { "C", 3                   },
    { "Node.Js", 2             },
    { "HTML & CSS", 1          },
    { "Reverse engineering", 5 }
  
  }
  
}

```
