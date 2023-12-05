# Logical-Physical-Data-Modeling
Deliverable A. Basic Conceptual Data Modeling:
In the basic conceptual data modeling task, I create an entity-relationship diagram using two entities: CLASSROOM and COURSE. Each entity has its attributes:
CLASSROOM: classroom ID, campus building, room number, room capacity, classroom style.
COURSE: course ID, course name, department, course number, and multiple standard course learning objectives.
The task involves drawing these entities with their attributes, noting that COURSE has a multi-valued attribute (the learning objectives). The focus is on establishing a relationship between these entities without considering the cardinality at this stage, using classic entity-relationship notation.


For Deliverable B, I am enhancing the conceptual data model from Deliverable A by adding constraints and detailed attribute information:
Include maximum and minimum cardinality to show relationships between CLASSROOM and COURSE.
Specify lists of values for certain attributes in each entity.
Business rules to incorporate:
A classroom can host multiple courses.
A course can be held in more than one classroom.
A classroom might not be used for any course.
A course might be online and not require a classroom.
For specific attributes, add data types, sizes, and permissible values:
Classroom style: Theater-style, Rows of seats, Groups of work tables, Computer classroom, Other.
Course learning objectives: Critical thinking, Subject knowledge, International applicability, Ethical decisions, Collegial working.


For Deliverable C, I need to create a logical data model based on the conceptual model from Deliverable B, using Crow's foot notation. This involves representing the entities (CLASSROOM and COURSE), their attributes, and the relationships between them, along with cardinality and other constraints specified earlier.


For Deliverable D, I created a physical data model of your logical model using MySQL Workbench. This step involves using the software's forward modeling feature to translate your logical model into actual database tables, complete with defined data types, sizes, and relationships as per your model.
