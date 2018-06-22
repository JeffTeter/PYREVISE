# PYREVISE
PYREVISE is a coorperative project intended to provide a Python implementation of the Revise program from UniVerse. This program allows the user to enter a command in the form of "PYREVISE {file name} {dictionary list}" to retrieve and update specific records from a UniVerse database. The "dictionary list" will be a list of fields that are identified and configured in the UniVerse dictionary using standard UniVerse dictionary structures. 

The PYREVISE program may be used to edit one or more records, delete an existing record or create a new record. When creating a new record, the program will check for a dictionary called "&NEXT.AVAILABLE&". If that dictionary is present, the integer stored in it will be incremented by one to produce the new record ID and the record ID will be tested, iteratively, until a blank record is found to be available. If that dictionary is not present, the user will be prompted to provide a record ID. 
