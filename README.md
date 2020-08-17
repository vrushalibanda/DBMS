# Database-Management-and-Applications
In this you will develop an Enhanced Entity Relationship Diagram (EERD) of an orthopedic clinic in Hayward. The database will be used to keep track of some aspects of healthcare business as described below.
The clinic is a small 7-physician clinic specializing in knee, elbow, hand, shoulder, hip, foot, ankle and other orthopedic problems. Besides seven physicians, the staff includes four nurses, two secretaries, and other employees filling various positions. Employee information including employee id, name, address, age, salary, should be recorded.
When a patient arrives for their first visit, a record of this patient is created where a patient ID is assigned and personal information including name, gender, age, address is recorded. During the first visit the patient is assigned to a physician who then becomes her primary care physician. A physician may be assigned to many patients or may not be assigned to anyone.
On the first and subsequent visits (if any), a patient needs to fill a form to provide the reason of visit. A nurse pre-examines the patient for heart rate, temperature, etc. and then a physician examines the patient and gives a diagnosis. For each visit, a visit id is assigned and the information described above (reason of visit, pre-examines results, and diagnosis) as well as date of visit is recorded.
For each visit, the physician may write one or more prescriptions to her patients. Each prescription is recorded with a prescription id and contains information about the drug used, dosage, and a date. Note that adding visit id attribute in the prescription entity can collect all the relevant information about the visit.
The clinic also maintains data on drugs. Each drug has a unique drug ID, description, expiry date, manufacturer, and price which are recorded. Any drug listed in the database may have a mild, moderate or severe interactions with a number of other drugs. Interaction type between two drugs must be captured. Use a unary relationship with interaction as an associative entity having type as a multivalue attribute.
For each visit, if the problem requires a certain type of surgery, it is scheduled at one hospital in the city. The clinic maintains data on related types of surgery, each with a surgery id and corresponding descriptions. The data on involved hospitals is also recorded with hospital id and related information such as name, address and descriptions. A hospital may or may not offer a certain type of surgery. The clinic also wants to keep track of each specific surgery, i.e. which visit led to what surgery and the hospital in which it was performed and other schedule details.
Some additional Business Rules/Assumptions:
1.	It is not necessary to track the secretary who schedules the appointment.
2.	It is desired to keep track of the nurse who do pre-examinations and the physician who do the examination.
3.	There are other types of employees in the clinic, but nurses and physicians are the only ones who have special attributes and relationships. The clinic keeps track of the specialty of each physician and the years of experience of each nurse.  
Draw an enhanced ER diagram for the problem described above.  Select appropriate attributes based on the information provided in this document and your understanding of the problem domain.   Clearly state any more assumptions you make about the business rules. 
1.	All entities
a.	The entities should be named as given in the problem
b.	Associative entities should be shown as a rounded corner rectangle
2.	Attributes 
a.	Note that all identifiers should be underlined
b.	Add suitable foreign keys to create the relationships
c.	Composite and multivalued attributes should be shown as appropriate
3.	Relationships
a.	Be sure you include all the relationships described in the problem	
b.	Choose appropriate names for the relationships
c.	Indicate all minimum and maximum cardinality constraints for all relationships.  
d.	For those cases where the constraints are not explicitly indicated, make suitable assumptions and clearly write them in your solution.  
e.	A many-many relationship with attributes should be shown as an associative entity.
f.	A ternary relationship should be shown as an associative entity.
4.	Subtype-Supertype hierarchy
Show the disjointness and completeness constraints.  Clearly indicate the attributes of the supertype and the attributes of the subtypes.  Also show the relationships as appropriate.  The attributes of the supertype should also include the subtype discriminator
Deliverable:
You may use any drawing tool for the diagram however, I would prefer Lucid Chart. The diagram can be copied and pasted into a Word document and submitted.  Any assumptions you make should be clearly stated in the Word document.
