# YieldExample<br />
**Created Date:** 9/30/2015<br />
**Last Updated:** 9/30/2015<br />
**Description:** A simple Synergy .NET Visual Studio project that demonstrates how to use the YIELD statement.<br />
**Platforms:** Windows<br />
**Products:** Synergy DBL; Synergy .NET<br />
**Minimum Version:** 10.1.1<br />
**Author:** Jerry Fawcett
<hr>

**Additional Information:** The YIELD statement was added in version 10.1.1. This simple example reads a file (as coded the DBLDIR:syntxt.ism) and demonstrates the syntax to call a method which contains the yield statement. The example has two methods that call into a routine which returns either yield mreturn value or yield exit. GetAllRecs method - reads all records in the file and causes the yield mreturn value to return a record at a time. Get10Recs method - reads 10 records from the file and then call yield exit to return. The records are displayed in a DataGridView control. 

Requirements:    Visual Studio 2015 and Synergy 10.1.1 or higher
