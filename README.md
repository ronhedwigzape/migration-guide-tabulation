## Migration 

Sample:
Old repository: missiriga
Your sample forked repository: mgsr-nabua 


### Repository Name

- The repository name depends on the pageant title and its location. Our naming convention uses when competition is a pageant and for ladies that has "Miss" on the pageant's title, it will be "miss" and location will be always combined so the result will be "missiriga" something like that. Another example is when competition is a pageant but in other format like "Miss Gay San Roque", we use the initials so it will be like this > "mgsr" then the location will be separated with a "-".  It will be separated with "-" because they start with initials. The result will be msgr-nabua.

```
missiriga > mgsr-nabua
```

### Repository Description

- The repository description also follows a convention. The format is like this **Tabulation System for `Pageant Title` (`The Pageant's Location e.g. Iriga, Camarines Sur`)**. 



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

In cropping the photos, place a temporary circle to to measure the candidate's face or team

Clear results, ratings, clear necessary elimination, arrangements, titles
