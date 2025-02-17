# Databricks Certified Data Engineer Associate Questions v2 & v3

## Suggestions

- [Practice from these notebooks throroughly](/files/data-engineering-with-databricksv314.dbc) and below pdf
  - [de-mod-0-get-started-with-pyspark-programming](/files/de-mod-0-get-started-with-pyspark-programming.pdf)
  - [de-mod-1-get-started-with-databricks-data-science-and-engineering-workspace](/files/de-mod-1-get-started-with-databricks-data-science-and-engineering-workspace.pdf)
  - [de-mod-2-transform-data-with-spark](/files/de-mod-2-transform-data-with-spark.pdf)
  - [de-mod-3-manage-data-with-delta-lake](/files/de-mod-3-manage-data-with-delta-lake.pdf)
  - [de-mod-4-build-data-pipelines-with-delta-live-tables](/files/de-mod-4-build-data-pipelines-with-delta-live-tables.pdf)
  - [de-mod-5-deploy-workloads-with-databricks-workflows](/files/de-mod-5-deploy-workloads-with-databricks-workflows.pdf)
  - [Udemy Practice](https://www.udemy.com/course/practice-exams-databricks-certified-data-engineer-associate/)[You can try this. Use Udemy for Bussiness for free]
  - [Udemy Practice](https://www.udemy.com/course/databricks-certified-data-engineer-associate-practice-tests/)[You can try this. Use Udemy for Bussiness for free]
- Practice [&#34;PracticeExam&#34;](/files/PracticeExam-DataEngineerAssociate.pdf) questions available in this repo.
- Every options in [&#34;PracticeExam&#34;](/files/PracticeExam-DataEngineerAssociate.pdf) question becomes a question in actual exam.
- Read [Databricks Certified Associate Data Engineer Exam](/files/DatabricksCertifiedAssociateDataEngineerExam.pdf) thoroughly.
- Read [Manage data with delta lake](/files/de-mod-3-manage-data-with-delta-lake.pdf)
- Read [Build pipeline with DLT](/files/de-mod-4-build-data-pipelines-with-delta-live-tables.pdf)

Repo [link](https://github.com/Amrit-Hub/Databricks-Certified-Data-Engineer-Associate-Questions)

## Topics

1. **Why might data not be available in a Delta Lake table?**
   - _Hint: Consider commands like `vacuum`, `merge`, or `optimize`._
2. **What does Delta Lake become in the context of a data platform?**
   - _Hint: Think about the concept of a single source of truth._
3. **What does a Delta table contain in terms of history, metadata, and data?**
   - _Hint: Does it have single or multiple files?_
4. **What is an advantage of Delta Lake over a traditional data lake?**
5. **Which component is a web application a part of in Databricks architecture?**
   - _Hint: Control plane or Data plane?_
6. **What operations need to be done outside of a Databricks repo?**
   - _Hint: Consider operations like pull, push, commit, or clone._
7. **What is an advantage of using a repo over notebook versioning in Databricks?**
   - _Hint: Consider branching._
8. **Is Delta Lake ACID compliant?**
9. **How can you avoid duplicates when merging data in a Delta Lake table?**
   - _Hint: `MERGE` command._
10. **What should you consider when using the `INSERT OVERWRITE` command?**
11. **What is the purpose of using Z-ordering in Databricks?**
    - _Hint: For query performance optimization._
12. **Why might the `COPY INTO` command not work in a particular code block?**
    - _Hint: [Refer to this documentation](https://docs.databricks.com/sql/language-manual/delta-copy-into.html)._
13. **What happens when using `Expect` or `Drop` on violation in Delta Live Tables (DLT)?**
    - _Hint: [Refer to this documentation](https://docs.databricks.com/workflows/delta-live-tables/delta-live-tables-expectations.html)._
14. **When should you use `GRANT ALL PRIVILEGES` in Unity Catalog?**
15. **When should you use `GRANT USAGE` in Unity Catalog?**
16. **What is an advantage of using array functions in Spark?**
17. **How do you set `processingTime` to 5 seconds in a streaming query?**
    - _Hint: Refer to the practice exam question._
18. **How do you configure a streaming query for continuous processing in a production environment?**
    - _Hint: Refer to practice exam Q36._
19. **Which physical object should you create for 10 tables so that other teams can use them in Databricks?**
20. **How can you delete metadata but retain the data files in a Delta table?**
    - _Hint: Consider the concept of an external table._
21. **What happens when a stream is marked as "Streaming Live" in Databricks?**
    - _Hint: Refer to the practice exam question._
22. **How can you mark a table as containing PII data in Databricks?**
    - _Hint: Use a `comment` during table creation._
23. **How can you describe a database in Databricks to get the path for `customer360`?**
24. **What is the advantage of a gold table over a silver table in Delta Lake?**
25. **What is the difference between a bronze table and a raw table in Delta Lake?**
26. **How do you identity silver or bronze in Databricks?**
    - _Hint: Refer to practice exam Q31._
27. **How do you create dependent tasks in a Delta Live Tables (DLT) pipeline?**
28. **How can you speed up query execution in Databricks?**
    - _Hint: Refer to the practice exam question._
29. **How can you prevent a specific block of code from running on Sundays in Databricks?**
30. **Where can you see data quality metrics in Delta Live Tables (DLT)?**
31. **How can you execute a Delta Live Tables (DLT) pipeline?**
32. **How can you save costs using a serverless SQL warehouse or control DBU usage?**
33. **If a manager is concerned about project over-costing, how can you save costs in Databricks?**
    - _Hint: Consider the impact of using serverless endpoints, auto-stop, etc._
34. **How can you reduce cluster costs in Databricks?**
    - _Hint: Consider adding an auto-stop setting in a SQL endpoint._
35. **Refer question Q40 from the practice exam?**
36. **Refer question Q1 from the practice exam?**
37. **Refer question Q3 from the practice exam?**
38. **Which command or method is more appropriate for accessing a table in PySpark: `spark.table("mytable")`, `spark.delta.table("mytable")`, or `spark.sql("mytable")`?**
39. **What is the JDBC driver name for SQLite when connecting via Spark?**
40. **Given two tables, `march_transaction` and `april_transaction`, how can you create a new table `all_transaction` without duplicates?**
    - _Hint: Consider using join, merge, or union._
41. **Refer question Q27 from the practice exam?**
42. **Refer question Q33 from the practice exam?**
43. **How do you check the failed status of a task in a Delta Live Tables (DLT) pipeline?**
44. **Which should be used to trigger alerts in Databricks: a webhook or an email alert?**
45. **How can you speed up query execution using cluster pools in Databricks?**

## Lessons Learned

No matter what, please attempt the practice exam thoroughly. The answers in each question becomes another question. You will have ample amount of time during assessment.
