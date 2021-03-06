---
layout: page
title: How to Ingest a Media File Bundled with Metadata (CSV, XML, API)
weight: 305
---

To enable more advanced content ingestion options, the provided CSV/XML samples can be extended to include multiple/custom metadata items, account specific settings, update action and advanced content ingestion options (for example, ingestion of multiple transcoding flavors, multiple thumbnails etc.) Each item element within the XML, and each line in the CSV, represent a single entry created in the publisher account. Each entry will be populated with the metadata listed in its item element and the content referenced from it. When submitted, the bulk upload XML/CSV is validated on the Kaltura server. The validation includes an inspection of the XML structure, and verification of elements' structure and order compliance with Kaltura's bulk upload XSD (XML schema). For more information see <a href="http://knowledge.kaltura.com/faq/what-bulk-upload-and-ftp-content-ingestion" target="_blank" title="What is bulk and FTP upload">Bulk Upload and FTP Upload</a>.

To ingest a media file bundled with Metadata:

1.  Select the Upload tab.
2.  Click **Download CSV/XML Samples**.
3.  Enter the metadata in the relevant fields.
4.  For more information on the XML custom data upload see the following:

* http://www.kaltura.com/api_v3/xsdDoc/?type=bulkUploadXml.bulkUploadXML#element-customDataItems
* http://www.kaltura.com/api_v3/xsdDoc/?type=bulkUploadXml.bulkUploadXML#element-customData

 
>Note: For any bulk actions that will create more than 5,000 entries (e.g., users), including categories bulk uploads, please contact your Kaltura representative to coordinate the upload.
