# Data Modeling Using Erwin Software
This was a project for a database design and development class. <br>
Screenshots of my work are provided according to the requirements. <br> 
(_As I am using the academic edition of Erwin, it does not allow for direct source file connection to Github._) <br><br>
**Project Instructions:** [View Here](/CIS3050-Project1_Fall_2023.pdf) <br>
**Project Reflection and Explanation of Functional Dependencies:** [View Here](https://github.com/sebastian-huynh/erwin-data-models/blob/9fb5132bcc191d736eebcc0142521b0424a3f917/EERD%20Functional%20Dependency%20Report.pdf) <br>
**Erwin Software Information** [View Here](https://www.erwin.com/products/erwin-data-modeler/) <br><br>
![Conceptual Model Image](https://github.com/sebastian-huynh/erwin-data-models/blob/239b3938574ee3e6e945bee849fc88ee2e896283/ERD%20conceptual%20view.png) <br>
**Conceptual level** of the entity relationship diagram displays the four independent, strong entities (_Department, Supervisor, Employee, and Project_). It also displays the bridging, associative entities between them (_Department_Employee, Supervisor_Employee, and Project_Assignment_) that are required to facilitate the many-to-many cardinalities. There is also the parent-child entity relationship seen between "Project" and "Task". <br><br>
![Logical Model Image](https://github.com/sebastian-huynh/erwin-data-models/blob/f51331a09ecd8196e35947fd267548b855da5bef/ERD%20logical%20view.png) <br>
**Logical level** of the entity relationship diagram expands on the conceptual and shows the attributes of each entity and identifies which function as the primary or foreign keys. <br><br>
![Physical Model Image](https://github.com/sebastian-huynh/erwin-data-models/blob/2403286b522ac199cc9beb2ddc75f63cc18113ba/ERD%20physical%20view.png) <br>
**Physical level** of the entity relationship diagram expands on the logical and shows the formatted datatypes for each attribute compatible with MS Sql Server. <br><br>
![Physical EERD Model Image](https://github.com/sebastian-huynh/erwin-data-models/blob/2403286b522ac199cc9beb2ddc75f63cc18113ba/EERD%20data%20model.png) <br>
**Physical EXTENDED Entity Relationship Diagram Level** extends the original ERD by showing super-subtype entities. In this case, department and employee are the supertypes and the subtypes inherit their attributes and are disjointed (_meaning an instance may not be part of two subtypes simultaneously_).
