<a href="/tutorials/">HOME</a>

# Imports 

There are many ways to get data into the system. Use one of the following methods:
- Manual Capture
- Auto Capture
- Single File Upload
- Zip File Upload
- OSINT LIAR Upload
- Csv Mapper Upload
- Api Endpoint Upload
- Paraben Upload



## File Uploads
OSINT LIAR does many upload options that can be confusing. In this section, we are only going to talk
about uploading a singular file and a zip file. This action can only be performed within the context 
of the OSINT LIAR Extension popup. 

### Single File Upload
Here is a short video of a PDF being uploaded. Any type of file can be uploaded. Only certain types
of files will have their content's indexed and made searchable. 

### Zip File Upload
A zip file, contains many files within it. OSINT LIAR was built with the ability to parse and scan each file
in the zip archive. This makes it very easy to import large batches of files quickly. Each file in the zip
is processed and annotated and its contents are indexed. Any existing selectors will automatically be identified
within the processed files. 

### OSINT LIAR Upload
This is how files can be passed between end users. The OSINT LIAR import file is a zip file is self-contained.
It can readily be read by other software programs, should you want to extend the functionality of the OSINT LIAR
ecosystem. OSINT LIAR imports are not destructive, if a record with the same unique id is encountered in an upload,
the data in the live system is not altered. 

### CSV Mapper Upload
When you need to bring data in from a spreadsheet, this is the goto tool. After uploading your csv file into
the user interface, the software will attempt to auto-match the columns of your spreadsheet into the data model
that exists. This powerful interface lets you bring in data quickly.  

### Api Endpoint Upload
TODO 

### Paraben Upload
Paraben, maker of E3 digital forensics tool can be imported into OSINT LIAR. Using E3's XML data export,
you extract data from the forensics tool and make the data more accessible to OSINT research practices. 

<a href="/tutorials/">HOME</a>
