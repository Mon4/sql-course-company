# sql-courses-company-app

This project is an sql database for a company that offers various types of courses, trainings and part-time studies.

Classes can be onsite, remote or hybrid. Languages can be various. If the language is other than Polish, there must also be an interpreter during the class to translate from the other language to Polish.

![study_meetings](https://github.com/Mon4/sql-courses-company-app/assets/44522588/97853fb3-cbf7-4d18-b41f-790eef5f6063)


Database contains data about clients, their courses.

![clients_classes](https://github.com/Mon4/sql-courses-company-app/assets/44522588/a9e91016-ef07-46ce-8235-1d1669a88851)

There is a list of students present or absent during study meeting.

![study_attendence_single](https://github.com/Mon4/sql-courses-company-app/assets/44522588/a5459e96-957f-4bbd-90d4-fc559c3e6498)

Studies are dividing for the reunions and subjects. During reunion are a few subjects but during another reunion can be another subjests. Students need at least 80% of attendenc to pass.

![study_attendence](https://github.com/Mon4/sql-courses-company-app/assets/44522588/b8faba3b-8a61-45c2-828c-e3d10e19da07)

Database contains data about clients payments for webinars, courses and studies. What is more there is a summed amount to pay.

![payments](https://github.com/Mon4/sql-courses-company-app/assets/44522588/b2d9b2fb-4729-409c-aabd-a2cb7d19f820)

Also contains data about students debts.

![debts](https://github.com/Mon4/sql-courses-company-app/assets/44522588/5f965612-11eb-44c4-8dda-bdeac097ce2b)

Sometimes it may happen that a student has two classes at the same time. So we have created a view to show this situation. This can help to prevent overlapping meetings/ changing meeting time.

![overlaping_meetings](https://github.com/Mon4/sql-courses-company-app/assets/44522588/6218090f-54e4-46bf-981e-3b120d7730b2)

Also contains data about our employees (lecturers and translators).

![employees](https://github.com/Mon4/sql-courses-company-app/assets/44522588/bfd7e06c-ce84-4f02-9ec8-de0e893438fa)



