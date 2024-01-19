FM-CombinePDFs
===========
This example takes multiple PDFs stored in container fields, combines them into a single document and then stores the resulting file in another container field. This requires a couple other freely available resources, listed below. 

By performing this action on the server, we reduce network latency and client side dependencies which also allows it to be compatible with WebDirect and FileMaker Go.

To run the demo:

1. Install the BaseElements plugin on FileMaker Server. Available here: http://www.goya.com.au/baseelements/plugin

2. Install PDFtk Server on the server. Available here: https://www.pdflabs.com/tools/pdftk-server/

3. Host this file in FileMaker server and run from a client like FileMaker Pro. 

Log in with:

user: Admin

pass: admin

NOTE: with newer version of Windows no longer needs to specify “cmd.exe /c ” at the beginning of a system command, so you can remove that in the script. Check in the script “server cat” on around line 125 when setting the variable “$cmd” and also line 156 setting the same variable to do the cleanup.

Blog post with more detailed explanation and instructions here:
https://www.soliantconsulting.com/blog/combine-pdfs-filemaker-fast-free