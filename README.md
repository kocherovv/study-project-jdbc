# StudyProject_JdbcCrud

Hi! it's my first study repo on github. 

It's a classic crud with no logic. 
I used mysql server and common java with jdbc for creating a repository with 3 entities: User, Post and Label.
User and Post are one-to-many, Post and Label - many-to-many.

I tryed to realized MVC pattern, so i created 3 package: repository, controller and service. 
In dto package i created simple data transfer objects and mappers for them.

The service layer is covered with tests, i used junit + Mockito.
