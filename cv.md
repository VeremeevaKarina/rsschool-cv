# Name
Karina Veremeyeva
## Contacts
* +375 (29) 154-83-17
* karina.veremeyeva@gmail.com
* [LinkedIn](https://www.linkedin.com/in/karinaveremeyeva)
## Summary
I'm studing at university. My major is information techonlogies.
I want to improve my knowledge of C# and Javascript. My current goal and to find a job as a Junior .Net Developer.
## Location
Gomel, Belarus
## Experience
Last year I developed web-prject for ordering tickets with using ASP.NET, Entity Framework.
## Education
**Gomel State Technical University** *(2017-2021)*
## Courses
**Epam .Net Development** *(2020)*
## Skills
* Back-end: C#, ASP.Net
* Front-end: HTML/CSS, Javascript, React
* Databases: MySql, MS Sql Server
* CVS: Git	
## Projects
* [My course work](https://github.com/VeremeevaKarina/CourseWork)
* [Project for university practice](https://github.com/VeremeevaKarina/WebProject)
* Some code example
```
public void CancelOrders(int loginId, int dateId)
        {
            var ordersToCancelIds = ordersRepository.GetOrders()
                .Where(q => !q.IsPaid 
                    && q.LoginId == loginId 
                    && q.DateId == dateId)
                .Select(q => q.Id);

            ordersRepository.RemoveRange(ordersToCancelIds);
        }
```
## Languages:
* Russian: *Native*
* English - *Intermiate (B1)*