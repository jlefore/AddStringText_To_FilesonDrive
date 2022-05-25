# AddStringText_To_FilesonDrive
I average around 20 invoices per month.
I use this code after i create my pdf invoices (raw) to add a descriptive string of text at the end of each invoice pdf.
The invoices from the TimeSolv software extract very little info for the pdf invoice. 
For example a raw pdf could be 'Client1_Invoice-1'. This is not descriptive enough. 
I prefer to add the 'MonthYear_MyCo.Name_Today'sDate' at the end of the raw pdf name above.
This code lets me see what files are in the folder (all though i can see them in a file manager) before i run and append all the names in folder. I display in a dataframe first to view the files. 
Then i run the function that appends the pdf files with the ending text 'MonthYear_MyCo.Name_Today'sDate'.
Here is an example of the finished pdf name 'Client1_Invoice-April2022_MyLLC_2022-05-24'
This saves me time and from mislabeling the invoices i create each month.
