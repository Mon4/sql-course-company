# Course Management Database System

<p align="justify">
This project is a comprehensive <strong>MS SQL database</strong> designed for a company offering <strong>courses, trainings, and part-time studies</strong>. It implements a robust, scalable architecture with <strong>over 50 interrelated tables</strong>, built to manage complex educational data efficiently. This project is built for performance, clarity, and real-world educational needs.
</p>

## 🔑 Key Features

- **Role-based access control**  
  Dedicated privileges for directors, employees, and students.

- **Automated workflows**  
  Implemented via stored procedures and functions to streamline operations.

- **Hierarchical data input**  
  Easily add entire study programs including multiple years, terms, and subjects in one go.

- **Insightful database views**  
  Quickly access important data like students with outstanding payments.

- **Standards-compliant**  
  Fully meets all specifications outlined in the `requirements.pdf`.


## Several key views are presented, highlighting important aspects of the system:

A view that lists all classes by type (onsite, remote, hybrid) along with the language of instruction. If the language is other than Polish, the view also shows whether an interpreter has been assigned, helping ensure compliance with translation requirements.

![study_meetings](https://github.com/Mon4/sql-courses-company-app/assets/44522588/97853fb3-cbf7-4d18-b41f-790eef5f6063)

The database includes information about clients and the specific types of courses they are enrolled in.

![clients_classes](https://github.com/Mon4/sql-courses-company-app/assets/44522588/a9e91016-ef07-46ce-8235-1d1669a88851)

The database tracks student attendance for each study meeting, listing those present or absent to support monitoring.

![study_attendence_single](https://github.com/Mon4/sql-courses-company-app/assets/44522588/a5459e96-957f-4bbd-90d4-fc559c3e6498)

Studies are divided into reunions and subjects. Each reunion includes several subjects, which may vary from one reunion to another. To pass, students must attend at least 80% of all classes.

![study_attendence](https://github.com/Mon4/sql-courses-company-app/assets/44522588/b8faba3b-8a61-45c2-828c-e3d10e19da07)

The database stores detailed payment information for webinars, courses, and studies, including individual transactions and the total amount due per client.

![payments](https://github.com/Mon4/sql-courses-company-app/assets/44522588/b2d9b2fb-4729-409c-aabd-a2cb7d19f820)

It tracks students' debts, making it easy to identify outstanding payments and manage financial follow-ups.

![debts](https://github.com/Mon4/sql-courses-company-app/assets/44522588/5f965612-11eb-44c4-8dda-bdeac097ce2b)

A dedicated view detects scheduling conflicts where a student is assigned to two classes at the same time, helping to prevent overlaps and support meeting time adjustments.

![overlaping_meetings](https://github.com/Mon4/sql-courses-company-app/assets/44522588/6218090f-54e4-46bf-981e-3b120d7730b2)

The database also includes detailed records of employees, including lecturers and translators, supporting scheduling, role assignment, and payroll management.

![employees](https://github.com/Mon4/sql-courses-company-app/assets/44522588/bfd7e06c-ce84-4f02-9ec8-de0e893438fa)



