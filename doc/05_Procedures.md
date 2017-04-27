# Python and R for SAS Developers

## Procedures

SAS Software includes pre-written procedures to perform functions, usually on complete datasets.  These pre-written functions include data manipulationm, statistical, graphical and utility functionality.

Following is a list of frequently used SAS procedures, and comparable code that could be used in Python and R.

### PROC APPEND

PROC APPEND is used to concatenate two SAS datasets together.  This can also be done with a DATA Step and multiple datasets on a SET statement.

Python:

    # Use concat() for a list of dataframes to append, or append() to add one new.
    dfnew = pd.concat([df1, df2, ... dfn])
    dfnew = df1.append(df2)

### PROC FCMP

### PROC FREQ

### PROC G*
SAS/GRAPH procedures are discussed in section [07. Graphics]([07_Graphics.md]).

### PROC MEANS

### PROC SORT

### PROC SUMMARY

### PROC TRANSPOSE

...


<table width="100%">
  <tr>
    <td width="33%" align="left"><a href="04_Functions.md">&lt;&lt;04. Functions</a></td>
    <td width="34%" align="center"><a href="00_TOC.md">Table of Contents</a></td>
    <td width="33%" align="right"><a href="06_Statistics.md">06. Statistics&gt;&gt;</a>></td>
  </tr>
</table>