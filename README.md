# FTWA
This project is a Family Tree Warehouse Application (FTWA) that needs to be developed using the Prolog language.

📌 What is the Purpose of the Project?

This application allows the user to store the information of the individuals belonging to their family and manage the family tree relationships between them. The user can add new people to the family tree, update some information of existing people, and make various person-based queries on the tree.

📌 Basic Features of the Project
Creating and Managing a Family Tree:
The user creates and manages a single family tree.

Person Information:
The following information is kept for each individual:

Gender (male/female)

Name and surname (unique)

Birth and death dates

Father and mother (one)

Children (one or more)

Adding and Updating People:

New individuals can only be added to the family tree as children.

Other relationships are calculated by the program, the user cannot add manually.

The update only covers birth and death dates.

Information Query:

Whether an individual is alive or not

Age

Level in the family tree (number of generations)

Type of relationship between two people (e.g. mother, father, brother, sister, uncle, aunt, cousin, etc.)

Viewing the Family Tree:
Can be printed as a meaningful and informative diagram in the console.

Relationship Types:
Relationships shown to the user are named in Turkish (Mother, Father, Son, Sister, Uncle, Aunt, Uncle, Aunt, Cousin, Nephew, Brother-in-law, Sister-in-law, Mother-in-law, Father-in-law, Bride, Groom, Brother-in-law, Sister-in-law, Sister-in-law, Brother-in-law).

Marriage Rules and Controls:

Marriage can only be made between suitable people. (Marriage with mother, father, sibling, uncle, aunt, grandmother, etc. is rejected.)

Both spouses must be over the age of 18 for marriage.

If the marriage is invalid, a warning is given and the transaction is rejected.

Date Controls:

Birth and death dates must be realistic.

For example, it is not possible for a child to be born after a person's death; the program prevents this.

📌 Additional Assumptions
There are no more than one person with the same first and last name.

Only one couple (husband and wife) can be hard-coded at the root (top) of the family tree, other individuals are added by the user.

The update only affects birth and death dates, previous operations remain valid.
