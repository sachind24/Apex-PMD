# Apex-PMD
1. Save "design" file in "pmd/Ruleset" folder download it from

   https://github.com/pmd/pmd/blob/master/pmd-apex/src/main/resources/category/apex/design.xml
 ![image](https://github.com/user-attachments/assets/96f16639-02c2-4dfe-b671-615fc947c7dc)

3. Use command FOR HTML FORMAT pmd check -d "C:\Users\Sachin\Documents\WS Dev Dev X OB\WS Dev X OB\force-app\main\default\classes" -f html -R "C:\pmd\Ruleset\design.xml" --report-file "C:\pmd\output.html"
4. FOR XLS FORMAT pmd check -d "C:\Users\Sachin\Documents\WS Dev Dev X OB\WS Dev X OB\force-app\main\default\classes" -f csv -R "C:\pmd\Ruleset\design.xml" --report-file "C:\pmd\output.xls"

TO RUN ALL RULES
1. Download quickstart from https://github.com/pmd/pmd/blob/main/pmd-apex/src/main/resources/rulesets/apex/quickstart.xml and create folder as below
![image](https://github.com/user-attachments/assets/0cfde265-a3ca-45f5-9588-b12558e7b0d0)
2. Download all rules from https://github.com/pmd/pmd/tree/main/pmd-apex/src/main/resources/category/apex and create folder as below
![image](https://github.com/user-attachments/assets/0fc4822f-327c-4885-b5a8-021127fb06de)
3. pmd check -d "C:\Users\Sachin\Documents\Hines Sprint 18\Hines\force-app\main\default\classes" 
-f csv -R "C:\pmd\rulesets\apex\quickstart.xml" --report-file "C:\pmd\output.xls"


