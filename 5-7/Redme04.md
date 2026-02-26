SELECT name, department, salary
FROM employees
WHERE salary BETWEEN 50000 AND 60000
ORDER BY salary ASC;

確認
   name    |   department   | salary
-----------+----------------+--------
 高橋 美咲 | マーケティング |  53000
 高田 太郎 | 営業           |  55000