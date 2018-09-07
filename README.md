## What is in this repo?

`PROCUREMENT` and `RDTE` justifications books (PDFs + attachments) harvested from the USD Comptroller website (http://comptroller.defense.gov/) for **2019**.


The catalog of files that were harvested can be found by looking at the `jbook_list.json` file:

## Each PDF file was..

- Downloaded
- Parsed for attachments
- Any attachments that were zip files was unzipped (typically represented as .zzz files)

by the included `fetch.php` script.


> **IMPORTANT NOTE**
>
You do NOT necessarily need to run this script - as all of the extracted files are included in this repo.  A log of each the extract is also included in `fetch.log`


## Why was this done?

The XML files included in this repo are used by the FedAPI platform, but could also be used by others who want easy access to the data files that are locked in the PDF files.
