REPOSITORY
Name
-> qotu.sn-iriga
Description
-> Tabulation System for Queen of the Universe (San Nicolas, Iriga City)



REPLACE IN FILES
Select the root folder "qotu.sn-iriga" in PHPStorm then press [CTRL + SHIFT + R]

bbsv-buhi
-> qotu.sn-iriga

Binibining San Vicente (Buhi, Camarines Sur)
-> Queen of the Universe (San Nicolas, Iriga City)

Binibining San Vicente
-> Queen of the Universe

5178
-> 5181



RENAME FILES
bbsv-buhi.sql
-> qotu.sn-iriga.sql



DOWNLOAD / CROP PHOTOS
Download the photos of the candidates, crop them in 300x300 dimensions, then rename the files properly (e.g. 01-weng-arines.jpg)

Place the photos inside /app/crud/uploads.

UPDATE .gitignore
Replace these lines:
[
!app/crud/uploads/01-miles-tiffany-kaalim.jpg
!app/crud/uploads/02-chabelita-molina.jpg
!app/crud/uploads/03-neoli-kryss-angeline-abarientos.jpg
!app/crud/uploads/04-erika-mae-recafranca.jpg
!app/crud/uploads/05-aaliyah-mae-mariscotes.jpg
!app/crud/uploads/06-mary-claire-chavez.jpg
!app/crud/uploads/07-hanna-grace-clavillas.jpg
!app/crud/uploads/08-maria-ericka-mae-ceneta.jpg
!app/crud/uploads/09-trisha-jane-lopez.jpg
!app/crud/uploads/10-mara-monte.jpg
!app/crud/uploads/11-hannah-paula-quebral.jpg
!app/crud/uploads/12-lian-shaine-naparato.jpg
]

with the filenames of your cropped photos
Example:

[
!app/crud/uploads/01-weng-arines.jpg
...
]



COMPLETE SETUP
- Perform necessary Database and CRUD updates.
- Export the clean database and place it into the project.



PERFORM INITIAL COMMIT
Commit your setup with message "Prepare for Queen of the Universe (San Nicolas, Iriga City)."

In cropping the photos, maglagay ka ng temporary circle to prepare the photo in circular form sa system

Also, clear mo muna yung results page sa initial commit (optional)