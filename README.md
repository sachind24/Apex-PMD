# Apex-PMD
1. Save Rule set file in folder https://github.com/pmd/pmd/blob/master/pmd-apex/src/main/resources/category/apex/design.xml
2. Use command FOR HTML FORMAT pmd check -d "C:\Users\Sachin\Documents\WS Dev Dev X OB\WS Dev X OB\force-app\main\default\classes" -f html -R "C:\pmd\Ruleset\design.xml" --report-file "C:\pmd\output.html"
3. FOR XLS FORMAT pmd check -d "C:\Users\Sachin\Documents\WS Dev Dev X OB\WS Dev X OB\force-app\main\default\classes" -f csv -R "C:\pmd\Ruleset\design.xml" --report-file "C:\pmd\output.xls"
