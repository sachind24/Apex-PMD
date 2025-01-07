# Apex-PMD
1. Save "design" file in "pmd/Ruleset" folder download it from

   https://github.com/pmd/pmd/blob/master/pmd-apex/src/main/resources/category/apex/design.xml
 ![image](https://github.com/user-attachments/assets/96f16639-02c2-4dfe-b671-615fc947c7dc)

3. Use command FOR HTML FORMAT pmd check -d "C:\Users\Sachin\Documents\WS Dev Dev X OB\WS Dev X OB\force-app\main\default\classes" -f html -R "C:\pmd\Ruleset\design.xml" --report-file "C:\pmd\output.html"
4. FOR XLS FORMAT pmd check -d "C:\Users\Sachin\Documents\WS Dev Dev X OB\WS Dev X OB\force-app\main\default\classes" -f csv -R "C:\pmd\Ruleset\design.xml" --report-file "C:\pmd\output.xls"
