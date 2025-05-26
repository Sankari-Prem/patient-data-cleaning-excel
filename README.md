# Task-1-
The Patient ID column contained very long numeric identifiers (e.g., 29872499824296.0), which were difficult to read and interpret.Extracted only the last 6 digits of the ID (e.g., 824296) to make it simpler.Used Excel formula  ="Patient"&RIGHT(A1,6)
Used Find and replace for gender column.Replaced "M" with Male and "F" with Female.
2016-04-29T16:08:27Z,this format is hard to read in scheduledday column. cleaned this timestamp into a readable format like: 29-Apr-2016 16:08:27.Formula used is =TEXT(DATEVALUE(LEFT(A1,10)) TIMEVALUE(MID(A1,12,8)), "dd-mmm-yyyy hh:mm:ss").
In scholarship,hipertension,diabetes,alcoholism,handcap and smsreceived columns finad and replace option is used.Replaced blank values with "0".
