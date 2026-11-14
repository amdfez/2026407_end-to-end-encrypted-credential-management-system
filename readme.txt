Project Name: End to End Encrypted Credential Management System
Students: 4
Names and Reg Numbers:
- Ahmad Faiz_2026407
- Zain Ul Abideen_2026800
- Ahmed Hanif_2026833
- Zohaib Waheed_2026816

Brief Description:-
It is a console-based Password Manager. It is a user credential vault made with C++. It lets users store, create, find and keep track of their website passwords. 
It also lets an administrator watch login activity and delete user accounts. When the program starts it reads stored accounts from a file using (fstream) and loads them into one‑dimensional arrays.
It also loads security logs into an audit matrix. To check logins the program uses a function that limits attempts. When a user logs in the program creates that user’s vault in memory,
with pointers. The vault grows automatically when more entries are added. Before any credential is written to disk, a char* pointer‑based cipher hides the password.
It uses the user’s Master Password as the key. This keeps the files encrypted and even the administrator cannot see the password. The program uses functions, loops, password strength checks and a 
recursive binary search to manage everyday vault tasks.
