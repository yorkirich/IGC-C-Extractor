# IGC-C-Extractor

To claim a declared flight in the UK XC League the pilot needs to enter their start, finish and optional intermediate points at the time of uploading their IGC file.  In today's world where scanning a task code is prevalent determining the coordinates takes a couple of minutes effort and a little knowledge.

This utility extracts the C records from a selected IGC and displays the coordinates in dd.ddddd format for easy cut and paste into the XC League a the point of claiming a declared flight.

Optionally, it can also create an .xctsk file from the decalaration which may be useful to analyse other pilots intentions on their flights.

Usage:
1. download the file to your phone or computer
2. click on it and it'll open a page in your browser from which you select an IGC file.  The IGC is analysed and all the C records in he IGC are displayed.  The relevant coordinates are also displayed in an easy to cut n paste format.
3.  click the convert button and it should create display the coordinates ont he screen and create the xctsk file

Tested on start/ finish IGCs generated by XCTrack, FlySkyHi and Oudie.  Also tested on  multi turnpoint declares created by XCTrack.  

The code is javascript wrapped in HTML.

Professional developers beware.  Written entirely by ChatGPT.  I've hardly even looked at the code and made no attempt to make it efficient nor robust.
