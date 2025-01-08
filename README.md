###########notebooks

Fabric code to read/write/transform files  as pandas.

1. connect to sharepoint from microsoft fabric
2. read files from microsoft fabric
3. merge excel files
4. write to sharepoint as csv.


order  of execution with details;
notebook : final_output_sp

call's the other notebooks from it.

notebook : merge_excel_files
reads files from microsoft fabric and merge's the excel files and writes to share point location as vsc file

notebook : common_functions

It contains all reusable function like reading files(csv, excel) from sharepoints, you can modify or add extra functions to existing code to read other files



##################pipeline

Generic email pipeline can be used for any project
pl_generic_email1.zip - is Generic email pipeline can be used for any project by simply importing into the pipeline in Micorosft fabric.

pl_stored_proc.zip - is sample pipeline show if stored procedure fails how we can pass params to  email pipeline .
