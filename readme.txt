-
-Ce projet est une application e-commerce simple, développée avec PHP, HTML, CSS, JavaScript et Bootstrap. Il s'agit d'une solution légère et facile à comprendre, idéale pour apprendre les bases du développement web sans utiliser de framework MVC
-
--
--
-
-
-
-
-
-
-
-
---- MILOU Mohamed

-
-
-
-
-
-
---
-
ALTER TABLE comments  add CONSTRAINT fr_Cmnt_Item 
FOREIGN key(Item_id_cmnt) REFERENCES items (ItemID ) 
on DELETE CASCADE 
on UPDATE CASCADE 

ALTER TABLE comments add CONSTRAINT fk_User_comnt 
FOREIGN KEY(User_id_cmnt ) REFERENCES users(UserID) 
on DELETE CASCADE on UPDATE CASCADE
