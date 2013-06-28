---
layout: post
title: File Formats for Google Docs API
url: http://apievangelist.com/2011/02/23/google-docs-file-formats-viewer-web-and-api/
source: http://apievangelist.com/2011/02/23/google-docs-file-formats-viewer-web-and-api/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/googleapps.jpg
---
{% include JB/setup %}I am defining various aspects of the Google Docs platform in conjunction with my Google Cloud Print Proxy work.
I need to know what is possible via the Google Docs Listing API for managing documents prior to cloud printing.
I am focusing on what file types and sizes are viable through the Google Docs Web Interface, Google Docs Viewer and the Google Docs Listing API.
The following formats are available for use in the Google Docs Viewer:

	Microsoft Word (.DOC, .DOCX)
	Microsoft Excel (.XLS, .XLSX)
	Microsoft PowerPoint 2007 / 2010 (.PPT, .PPTX)
	Apple Pages (.PAGES)
	Adobe Illustrator (.AI)
	Adobe Photoshop (.PSD)
	Autodesk AutoCad (.DXF)
	Scalable Vector Graphics (.SVG)
	PostScript (.EPS, .PS)
	TrueType (.TTF)
	XML Paper Specification (.XPS)

With Google Docs Business Accounts any document type can be uploaded via the Google Doc Web Interface, and any document can be created or uploaded via the Google Docs List API.
There are specific documents types that can be uploaded as Google Documents.
Google Documents
You can import in the following file types for Google Docs:

	.gif - image/gif - Graphics Interchange Format
	.odt - application/vnd.openxmlformats-officedocument.wordprocessingml.document - Open Document Format
	.doc - application/msword - Microsoft Word Format
	.jpeg - image/jpeg - Joint Photographic Experts Group Image Format
	.html - text/html - HTML Format
	.txt - text/plain - TXT File
	.pdf - application/pdf - Portable Document Format
	.png - image/png - Portable Networks Graphic Image Format
	.rtf - application/rtf - Rich Format

Google Docs have a maximum import file size of 512000 KB or 512 MB.
You can export in the following file types for Google Docs:

	.doc - application/msword - Microsoft Word Format
	.html - text/html - HTML Format
	.jpeg - image/jpeg - Joint Photographic Experts Group Image Format
	.odt - application/vnd.openxmlformats-officedocument.wordprocessingml.document - Open Document Forma
	.pdf - application/pdf - Portable Document Format
	.png - image/png - Portable Networks Graphic Image Format
	.rtf - application/rtf - Rich Format
	.svg 	Scalable Vector Graphics Image Format
	.txt - text/plain - TXT File
	zip 	ZIP archive. Contains the images (if any) used in the document

Google Drawings
You can import in the following file types for Google Drawings:

	.wmf - image/x-wmf - Windows Metafile

Google Drawings have a maximum import file size of 512000 KB or 512 MB.
You can export in the following file types for Google Drawings:

	.jpeg - image/jpeg - Joint Photographic Experts Group Image Format
	.pdf - application/pdf - Portable Document Format
	.png - image/png - Portable Networks Graphic Image Format
	.svg - image/svg+xml - Scalable Vector Graphics Image Format

Google Presentations
You can import in the following file types for Google Presentations:

	.ppt  - application/vnd.ms-powerpoint - Powerpoint Format
	.pps - application/vnd.ms-powerpoint - Powerpoint Format

Google Presentations have a maximum import file size of 1048576 KB or 1049 MB.
You can export in the following file types for Google Presentations:

	.pdf - application/pdf - Portable Document Format
	.png - image/png - Portable Networks Graphic Image Format
	.ppt  - application/vnd.ms-powerpoint - Powerpoint Format
	swf - application/x-shockwave-flash - Flash Format
	.txt - text/plain - TXT File

Google Spreadsheets
You can import in the following file types for Google Spreadsheets:

	.ods - application/vnd.openxmlformats-officedocument.spreadsheetml.sheet - ODS (Open Document Spreadsheet)
	.xls - application/vnd.ms-excel - XLS (Microsoft Excel)
	.txt - text/plain - TXT File
	. tsv  - text/tab-separated-values - TSV (Tab Separated Value)

Google Spreadsheets have a maximum import file size of 10486760 KB or 10486 MB.
You can export in the following file types for Google Spreadsheets:

	.xls - application/vnd.ms-excel - XLS (Microsoft Excel)
	.csv 	CSV (Comma Seperated Value)
	.png - image/png - Portable Networks Graphic Image Format
	.ods - application/vnd.openxmlformats-officedocument.spreadsheetml.sheet - ODS (Open Document Spreadsheet)
	. tsv  - text/tab-separated-values - TSV (Tab Separated Value)
	.html - text/html - HTML Format


All other types of files uploaded to Google Docs for storage, and if they are not converted into a Google Document, can be a maximum of 1GB. PDF documents uploaded to Google Docs can only be exported as PDF documents.
With the ability to upload ANY file type to Google Docs with a size of up to 1GB, it makes it a very viable Cloud Storage platform.
The number of documents Google has support for uploading and exporting via the Google Docs Listing API makes it an extremely viable document conversion platform.
Also Google provides advanced document management tools such as OCR and language translation on upload, along with resumable uploads.
Throw in mobile viewing, editing and cloud printing of documents.  You have thebuildingblocks for a pretty amazing cloud document management system.
Related articles

	Optical Character Recognition (OCR) with Google Docs API (kinlane.com)
	12 new file formats in the Google Docs Viewer (gmailblog.blogspot.com)
	Google Docs File Size Limitations (kinlane.com)

