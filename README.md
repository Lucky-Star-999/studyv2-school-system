# School Management System
A microservice project for learning basic backend concepts

## Project Description
### User
**User**: Admin, Student, Teacher

### Description
- A **teacher** can teach multiple **subjects**.  
- A **student** can study multiple **subjects**.  
- In a **subject**, there is one **teacher** and multiple **students**. The **period** when they study together called a **class**.
- A **class** has many **periods**, and a **class** takes place in a **classroom**.
- Assume that a **period** lasts one hour. The first **period** in a day is 7:00AM, and the last period in a day is 6:00PM.
- There may be multiple **teachers** teach the same **subject**.
- A **subject** has a fixed numbers of **periods** although the **subject** may be teached by multiple **teachers** with many **classes**.
- The schoolday is available from Monday to Saturday.


> **For example**:  
A **subject** Math teached by **teacher** A, B. The **subject** has 3 periods. The **teacher** A teaches it on Monday (7AM-10AM, **classroom** A1) and Friday (1PM-4PM, **classroom** B3). The **teacher** B teaches it on Thursday from 2PM to 5PM, at **classroom** A2.

- **Student** can see their schedule, including **subject**, **classroom**, **teacher** and **time (periods)**.
- **Teacher** can see their schedule, including **subject**, **classroom**, **students** in his or her **class** and **time (periods)**.
- **Admin** can see everything.
- Some advanced features such as **Reset passwords**, **Change password with email**, etc. should be **ignored**.
