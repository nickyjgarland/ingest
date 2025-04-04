# Metadata Template

This document provides guidance for completing the Metadata Template for deposition into ADS Ingest. Accurate and complete metadata ensures that your digital deposit is discoverable, usable, and properly preserved in our archive.

## Instructions

Prior to using the Ingest system, you should organise the data you would like to deposit and create appropriate metadata.

Download the metadata template (linked below) and complete for all objects that you would like to ingest. Each line of the template will describe a single object that you would like to deposit.

Please complete this template prior to the submitting your data via ADS Ingest, as this file will be utilised to validate the files that you are depositing with the ADS.


!!! info "Important"

    It is important that the details listed below are correctly formatted to allow for autonomous ingest of data into the system. Any errors will be highlighted during the deposit process but must be amended before the deposition can proceed.

## Template Download

A .csv version of the Metadata template can be downloaded from the following link:

[Download Template](assets/metadata_template.xlsx){ .md-button .md-button--primary }

The Template contains example data to assist in complete the form. Please delete this data before uploading via the Ingest system.

## Field Guidelines

The following section provides detailed guidance for each field in the metadata template including descriptions and examples.

![metadata template](./assets/metadata_template_image.png)

### __Filename__
Enter name of file. Please include only one filename per row, including the file extension.  If you are depositing shapefiles or other objects where multiple files make up a single item, please include only one filename. 

* Example - *012345_Archaeological_Site_London_Report.pdf*
* Format - Free text field

### __Type__
Enter the type of file uploaded from the drop down provided. This field has a [controlled vocabulary](./appendix_controlled_vocabs.md).

* Example - *Photograph*
* Format - Controlled Vocabulary

### __Title__
Enter a short descriptive title for users of the ADS website and for ongoing management. Please ensure that this title is unique within your collection.

* Example - *Land at Archaeological Site, London - Archaeological Evaluation Report*
* Format - Free text field

### __Description__
Enter a short description, expanding upon the title, for users of the ADS website, and for ongoing management.  The description may include information about the contents and purpose of the file, along with any dependencies or relationships to other files.

* Example - *East facing shot of ditch [001]*
* Format - Free text field

### __Tag__
Enter any tags or keywords that describe the content of the item.  These descriptive terms or phrases can include particular places, people, time periods (where interpretation allows), or subjects.  Please separate multiple terms or phrases with a comma (,).

* Example - *Roman, Ditch*
* Format - Free text field

### __Creator__
Enter the names of any individuals you would like to credit with the creation of, or contribution to, this file.  Please separate multiple names with commas (,). If the creator has an [ORCID](https://orcid.org/)  please put this in brackets () at the end of the name. If there is no known or relevant person who can be named as Creator, leave blank but ensure the [Copyright Holder](#copyright-holder) field is completed.

* Example - *Nicholas Jones (https://orcid.org/1234-5678-9101-1121)*
* Format - Free text field

### __Copyright Holder__
Enter the person or organisation that holds Copyright for this digital object. Please separate multiple names with commas (,). If this is a named person please follow the Guidance as for [Creator](#creator). If the Copyright Holder is an organisation please enter the name followed by *(org)*.

* Example - *ARC Company Ltd (org)*
* Format - Free text field

### __Creation History__
Enter a short description of how this object was created, including what tools/software/processing was involved. Please separate multiple entries with commas (,).

* Example - *Microsoft Word, Adobe*
* Format - Free text field

### __Language__
Enter a language if the digital object contains text elements, or integrated metadata. This is not necessary for image content. Please separate with commas (,) if multiple languages are included.

* Example - *English*
* Format - Free text field

### __Date File Digitally Created__ 
Enter the date this digital object was created. If this is a scan or replication of historic works please use the date of the digital creation.

* Example - *23/03/2021*
* Format - Date (DD/MM/YYYY format)

### __Additional Metadata__
Enter a filename for any additional metadata. For specific data types, the ADS requires additional technical metadata. Guidance on this technical metadata is provided in the [ADS Guidelines for Depositors](https://archaeologydataservice.ac.uk/advice/Downloads.xhtml). Please use either  an ADS generated template. If using multiple files, separate with a comma (,).

* Example - *012345_ADS_database_metadata_Enviro_v2.xlsx*.
* Format - Free text field

### __Survey Area (Hectares)__ 
For "Geophysics" data type only. Enter the total area of the geophysical survey in hectares. Decimal points are allowed.

* Example - *3.6*
* Format - Numeric