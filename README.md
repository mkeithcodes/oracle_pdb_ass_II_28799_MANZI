Individual Assignment II: Oracle Pluggable Databases management.
Manzi keith. ID:28799

Task 1: Create a New Pluggable Database:

I created a pluggable database called ke_pdb_28799
# PLUGGABLE DATABASE
CREATE PLUGGABLE DATABASE ke_pdb_28799
ADMIN USER admin_ke IDENTIFIED BY "kePass123"
FILE_NAME_CONVERT = ('C:\app\oracle\oradata\ORCL\pdbseed\', 
                     'C:\app\oracle\oradata\ORCL\ke_pdb_28799\');


Task 2: Create and Delete a PDB
A PDB was created and named ke_to_delete_pdb_28799 

Task 3: Oracle Enterprise Manager (OEM)

I logged in the oracle enterprise manager as the screenshot shows:
<img width="932" height="375" alt="OEM DASH 1" src="https://github.com/user-attachments/assets/6aa5191c-0467-428a-9fb7-f45a969335e1" />


Task 4: Documentation & Reporting
The above readme reports all the tasks and explanations i have completed on oracle pluggable database management. 
