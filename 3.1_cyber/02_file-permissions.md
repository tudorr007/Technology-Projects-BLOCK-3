# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)

### Questions

1.  Who owns the file? group3
2.  What are the default permissions? read/write

### Reflection

Why is file ownership important in Linux systems?
it controls who can access the files
------------------------------------------------------------------------

## Task 2 --- Restrict File Permissions

Run:

    chmod 600 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)

### Questions

1.  Who can read the file now? only the owner
2.  Who cannot access it? other users


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)

### Questions

1.  Who can access the file now? anyone can read, write or execute the file
2.  Why might this configuration be dangerous? cause it gives access to everyone and they can edit or delete the file

