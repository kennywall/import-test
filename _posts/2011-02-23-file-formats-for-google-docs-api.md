---
layout: post
title: "File Formats for Google Docs API"
url: 'http://kinlane.com/2011/02/23/google-docs-file-formats-viewer-web-and-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/googleapps.jpg'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/googleapps.jpg" alt="" width="240" align="right" />I am defining various aspects of the [Google Docs][1] platform in conjunction with my [Google Cloud Print Proxy][2] work.

I need to know what is possible via the [Google Docs Listing API][3] for managing documents prior to cloud printing.

I am focusing on what file types and sizes are viable through the Google Docs Web Interface, Google Docs Viewer and the Google Docs Listing API.

The following formats are available for use in the Google Docs Viewer:

  * Microsoft Word (.DOC, .DOCX)
  * Microsoft Excel (.XLS, .XLSX)
  * Microsoft PowerPoint 2007 / 2010 (.PPT, .PPTX)
  * Apple Pages (.PAGES)
  * Adobe Illustrator (.AI)
  * Adobe Photoshop (.PSD)
  * Autodesk AutoCad (.DXF)
  * [Scalable Vector Graphics][4] (.SVG)
  * PostScript (.EPS, .PS)
  * TrueType (.TTF)
  * XML Paper Specification (.XPS)
With Google Docs Business Accounts any document type can be uploaded via the Google Doc Web Interface, and any document can be created or uploaded via the Google Docs List API.

There are specific documents types that can be uploaded as Google Documents.

**Google Documents**

You can import in the following file types for Google Docs:

  * <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/PDF_red.jpg" alt="" width="150" align="right" />
  * .gif - image/gif - [Graphics Interchange Format][5]
  * .odt - application/vnd.openxmlformats-officedocument.wordprocessingml.document - Open Document Format
  * .doc - application/msword - Microsoft Word Format
  * .jpeg - image/jpeg - [Joint Photographic Experts Group][6] Image Format
  * .html - text/html - HTML Format
  * .txt - text/plain - TXT File
  * .pdf - application/pdf - Portable Document Format
  * .png - image/png - Portable Networks Graphic Image Format
  * .rtf - application/rtf - Rich Format
Google Docs have a maximum import file size of 512000 KB or 512 MB.

You can export in the following file types for Google Docs:

  * <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/microsoft-powerpoint.png" alt="" width="150" align="right" />
  * .doc - application/msword - Microsoft Word Format
  * .html - text/html - HTML Format
  * .jpeg - image/jpeg - Joint Photographic Experts Group Image Format
  * .odt - application/vnd.openxmlformats-officedocument.wordprocessingml.document - Open Document Forma
  * .pdf - application/pdf - Portable Document Format
  * .png - image/png - Portable Networks Graphic Image Format
  * .rtf - application/rtf - Rich Format
  * .svg Scalable Vector Graphics Image Format
  * .txt - text/plain - TXT File
  * zip ZIP archive. Contains the images (if any) used in the document
**Google Drawings**

You can import in the following file types for Google Drawings:

  * .wmf - image/x-wmf - Windows Metafile
Google Drawings have a maximum import file size of 512000 KB or 512 MB.

You can export in the following file types for Google Drawings:

  * .jpeg - image/jpeg - Joint Photographic Experts Group Image Format
  * .pdf - application/pdf - Portable Document Format
  * .png - image/png - Portable Networks Graphic Image Format
  * .svg - image/svg xml - Scalable Vector Graphics Image Format
**Google Presentations**

You can import in the following file types for Google Presentations:

  * .ppt - application/vnd.ms-powerpoint - Powerpoint Format
  * .pps - application/vnd.ms-powerpoint - Powerpoint Format
Google Presentations have a maximum import file size of 1048576 KB or 1049 MB.

You can export in the following file types for Google Presentations:

  * <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/google/google-doc-on-iphone.png" alt="" width="200" align="right" />
  * .pdf - application/pdf - Portable Document Format
  * .png - image/png - Portable Networks Graphic Image Format
  * .ppt - application/vnd.ms-powerpoint - Powerpoint Format
  * swf - application/x-shockwave-flash - Flash Format
  * .txt - text/plain - TXT File
**Google Spreadsheets**

You can import in the following file types for Google Spreadsheets:

  * .ods - application/vnd.openxmlformats-officedocument.spreadsheetml.sheet - ODS (Open Document Spreadsheet)
  * .xls - application/vnd.ms-excel - XLS (Microsoft Excel)
  * .txt - text/plain - TXT File
  * . tsv - text/tab-separated-values - TSV (Tab Separated Value)
Google Spreadsheets have a maximum import file size of 10486760 KB or 10486 MB.

You can export in the following file types for Google Spreadsheets:

  * .xls - application/vnd.ms-excel - XLS (Microsoft Excel)
  * .csv CSV (Comma Seperated Value)
  * .png - image/png - Portable Networks Graphic Image Format
  * .ods - application/vnd.openxmlformats-officedocument.spreadsheetml.sheet - ODS (Open Document Spreadsheet)
  * . tsv - text/tab-separated-values - TSV (Tab Separated Value)
  * .html - text/html - HTML Format
<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-mimeo.png" alt="" width="350" align="right" /> All other types of files uploaded to Google Docs for storage, and if they are not converted into a Google Document, can be a maximum of 1GB. PDF documents uploaded to Google Docs can only be exported as PDF documents.

With the ability to upload ANY file type to Google Docs with a size of up to 1GB, it makes it a very viable Cloud Storage platform.

The number of documents Google has support for uploading and exporting via the Google Docs Listing API makes it an extremely viable document conversion platform.

Also Google provides advanced document management tools such as [OCR][7] and [language translation][8] on upload, along with resumable uploads.

Throw in mobile viewing, editing and cloud printing of documents. You have thebuildingblocks for a pretty amazing cloud document management system.

######  Related articles

  * [Optical Character Recognition (OCR) with Google Docs API][7] (kinlane.com)
  * [12 new file formats in the Google Docs Viewer][9] (gmailblog.blogspot.com)
  * [Google Docs File Size Limitations][10] (kinlane.com)

   [1]: http://docs.google.com
   [2]: http://www.kinlane.com/2011/02/google-cloud-print-proxy-cloud-printer/
   [3]: http://code.google.com/apis/documents/
   [4]: http://www.w3.org/Graphics/SVG/ (Scalable Vector Graphics)
   [5]: http://en.wikipedia.org/wiki/Graphics_Interchange_Format (Graphics Interchange Format)
   [6]: http://en.wikipedia.org/wiki/Joint_Photographic_Experts_Group (Joint Photographic Experts Group)
   [7]: http://www.kinlane.com/2011/02/optical-character-recognition-ocr-with-google-docs-api/
   [8]: http://www.kinlane.com/2011/02/document-translation-with-google-docs-api/
   [9]: http://gmailblog.blogspot.com/2011/02/12-new-file-formats-in-google-docs.html
   [10]: http://www.kinlane.com/2011/02/google-docs-file-size-limitations/
