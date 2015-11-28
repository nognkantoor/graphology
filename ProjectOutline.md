# Project Outline #

## Introduction ##

The four freedoms are:
  * Freedom 0: The freedom to run the program for any purpose.
  * Freedom 1: The freedom to study and modify the program.
  * Freedom 2: The freedom to copy the program so you can help your neighbor.
  * Freedom 3: The freedom to improve the program, and release your improvements to the public, so that the whole community benefits.

There is no generally available software that meets those four criteria.  This projects attempts to remedy that situation.

## Details ##

### Spreadsheets ###

The Open Document Format was chosen for the spreadsheets as it is an ISO standard. (ISO/IEC 26300:2006/Amd 1:2012 - Open Document Format for Office Applications (OpenDocument) v1.1.)  Tools that can utilize this format are freely available.  This file format is also unencumbered by patents.

ISO/IEC 29500 is, according to its own specifications, suitable only for documents in a legacy file format. That eliminates it from consideration for documents that are to be created for future usage. This file format is covered by both patents and trade secrets.

### Databases ###

SQLite was chosen as the database. The primary factors in selecting this database engine are:
  * All tables are combined into one file --- easy transportability of individual databases;
  * It is distributed under a public domain license;
  * It is not encumbered by any known patents or trade secrets;
  * Platform independence;
    * It has been ported to a number of operating systems;
    * It has been ported to a number of programming languages;



### Stand Alone Tools ###

The tools will be written in Python.

### OOo Extensions ###

Once the bugs have been ironed out of the stand alone tools, they will be rewritten as extensions for LibreOffice and Apache Open Office.