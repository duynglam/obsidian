
*through bullets and table. short eli5 quick note.*

### first thing first
-   in common: both are API-related
-   in different
    -   CRUD: basic API sets
    -   REST: how you design your API

### into details

**CRUD**
-   abbr: Create - Read - Update - Delete
-   basic functions of a database
-   user directly process files or data objects
-   data & files are passives

Example: Manage action in book sites

| Name | Desc | SQL |
| --- | --- | --- |
|Create |Add book record to database |Insert|
|Read| Retrieve result that match keyword| Search|
|Update| Change book info| Update|
|Delete| Remove book info from database| Delete|


⏛

**REST**
-   works on object performance
-   each action is defined through a URL
-   theses are not action between data object
-   it reflects actions/ relationship to other resources

Example: Comment interaction between users

 Name | Desc | SQL |
| --- | --- | --- |
|Create |Add new comment |Insert|
|Read| Display comment (s)| Search|
|Update| Edit comment| Update|
|Delete| Remove comment| Delete|

the whole action doesnt’t stay in one place. the R in URL stands for resource. REST is all about resources. it takes different resources to complete an action in REST: the post he/she comments; a comment he/she responses to.

### to sum up
**CRUD** 
- basic APIs for database and static data storage
- pre-setup action for basic operations in database applications

**REST** 
- high level API for web and other reactive platform/ systems
- interact with complex systems
- popular design styles for web APIs (among other applications)