SELECT name, department
FROM employees
WHERE department <> '営業'
  AND salary >= 55000;

確認
  name    |   department
-----------+----------------
 田村 花子 | マーケティング