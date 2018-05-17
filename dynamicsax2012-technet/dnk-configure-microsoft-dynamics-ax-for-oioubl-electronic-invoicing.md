﻿---
title: (DNK) Configure Microsoft Dynamics AX for OIOUBL electronic invoicing
TOCTitle: (DNK) Configure Microsoft Dynamics AX for OIOUBL electronic invoicing
ms:assetid: 4706d9e1-0f3f-4019-a522-bb55a33065eb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231394(v=AX.60)
ms:contentKeyID: 36056907
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- electronic invoicing
- OIOUBL
---

# (DNK) Configure Microsoft Dynamics AX for OIOUBL electronic invoicing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use electronic invoicing in Microsoft Dynamics AX to send electronic invoices to the government in the Offentlig Information Online Universal Business Language (OIOUBL) format.

The electronic invoices and credit notes that you generate include required information, such as the contact person, invoice number, and address information. Validation rules are applied when invoices are generated so that you can verify that the correct information has been entered. If you find errors, you can correct the errors before you submit the invoices to the government.

To configure Microsoft Dynamics AX for OIOUBL electronic invoicing, you must set up folders to save the error messages, .xml files, and OIOUBL files. You must also set up Application Integration Framework (AIF) and batch processing. For more information about AIF and batch processing, see [(DNK) Set up AIF for OIOUBL electronic invoicing](dnk-set-up-aif-for-oioubl-electronic-invoicing.md) and [(DNK) Set up batch processing for OIOUBL electronic invoicing](dnk-set-up-batch-processing-for-oioubl-electronic-invoicing.md).

To set up the folders, follow these steps:

1.  Set up the following folder structure in a shared location that can be accessed from the Application Object Server (AOS) computer and from any client computers that are used as batch servers in your system. Set up the following folder structure for project invoices:
    
      - \\\\Server\\OIOUBL\\Project\\Error
    
      - \\\\Server\\OIOUBL\\Project\\Processed files
    
      - \\\\Server\\OIOUBL\\Project\\Source
    
      - \\\\Server\\OIOUBL\\Project\\Target
    
      - \\\\Server\\OIOUBL\\Project\\XSLT
    
    Set up the following folder structure for sales invoices:
    
      - \\\\Server\\OIOUBL\\Sales\\Error
    
      - \\\\Server\\OIOUBL\\Sales\\Processed files
    
      - \\\\Server\\OIOUBL\\Sales\\Source
    
      - \\\\Server\\OIOUBL\\Sales\\Target
    
      - \\\\Server\\OIOUBL\\Sales\\XSLT
    
    The folders are used as follows:
    
      - Error – Used to save error messages that are generated when the .xml file is converted to the OIOUBL format.
    
      - Processed files – Used to save documents after they are processed. The documents are moved from the Target folder to this folder.
    
      - Source – Used to save the .xml file that is generated by Microsoft Dynamics AX.
    
      - Target – Used to save the OIOUBL file after the .xml file has been processed.
    
      - XSLT – Used to save the eProjectInvoice\_DK\_OIOUBL or eSalesInvoice\_DK\_OIOUBL file.

2.  Copy the following files from the Microsoft Dynamics AX setup folder to the locations specified in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>File</p></th>
    <th><p>Location</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>eProjectInvoice_DK_OIOUBL.xsl</p></td>
    <td><p>\\Server\OIOUBL\Project\XSLT</p></td>
    </tr>
    <tr class="even">
    <td><p>eSalesInvoice_DK_OIOUBL.xsl</p></td>
    <td><p>\\Server\OIOUBL\Sales\XSLT</p></td>
    </tr>
    </tbody>
    </table>


## See also

[(DNK) Set up customer accounts for OIOUBL electronic invoicing](dnk-set-up-customer-accounts-for-oioubl-electronic-invoicing.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).
