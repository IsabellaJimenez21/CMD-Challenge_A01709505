# CMD-Challenge_A01709505
## Isabella Jim[enez Villeda A01709505
1. echo hello world
2. pwd (Print Working Directory)
3. ls -1
4. cat access.log
5. tail -n 5 access.log
6. touch take-the-command-challenge
7. mkdir -p tmp/files
8. cp take-the-command-challenge tmp/files
9. mv take-the-command-challenge tmp/files
10. ln -s tmp/files/take-the-command-challenge take-the-command-challenge
11. rm -rf -- ./* ./.*
12. find . -type f -name "*.doc" -delete
13. grep "GET" access.log
14. grep -l "500" *
15. find . -type f -name "access.log*"
16. grep -rh --include="access.log*" "500" .
17. grep -hoE '([0-9]{1,3}\.){3}[0-9]{1,3}' **/access.log*
18. ls -l | wc -l
19. sort access.log
20. grep "GET" access.log | wc -l
21. tr ';' '\n' < split-me.txt
22. seq 1 100 | tr '\n' ' '
23. find . -name "*.txt" -exec sed -i 's/challenges are difficult//g' {} +
24. awk '{sum += $1} END {ptac reverse-me.txtrint sum}' sum-me.txt
25. find . -type f -exec basename {} \;
26. find . -type f | while read file; do mv "$file" "${file%.*}"; done
27. find . -maxdepth 1 -type f -exec basename {} \; | tr ' ' '.'
28. find . -type f -name "*.tf" -exec dirname {} \; | sort -u
29. find . -type f -name '[0-9]*' -exec basename {} \;
30. sed -n '25p' faces.txt
31. tac reverse-me.txt
32. awk '!seen[$0]++' faces.txt
33. cat random-numbers.txt | sort|uniq | factor | awk 'NF==2'| wc -l
34. awk 's[$1]++{print $1}' access.log*
35. grep -h -B1 404 **/access.log*|grep -vE '404|--'
36. or f in t*; do cmp -s bas* $f || echo $f; done
37. find . -name "*flag.txt" -exec cat "{}" \;
38. grep -P "\t" * | wc -l
39. find . -type f ! -name "*.txt" ! -name "*.exe" -delete
40. find . -name "-*" -delete
41. cat * | sort -n -k2 | uniq
42. grep "\bLISTEN\b" netstat.out|grep -oP "tcp\s+.*:\K\d+"|sort -nr
