<!DOCTYPE html>
<html>
<body>
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<div id="mdiv">
<p>
<h2>Event Badge Submission</h2><br>
<label for="pname">Project Name:</label>
<input type="text" id="pname" name="pname"><br><br>
<label for="linkweb">Link to the Event Website:</label>
<input type="text" id="linkweb" name="linkweb"><br><br>
</p>
<h2>Speaker Demographics</h2>
<input type="checkbox" id="sdcb">This event commits to Speaker Diversity & Inclusion.
<p>  
Detail the Process for measuring Speaker Demographics.<br><input type="text" id="sddsc" name="sddsc"><br><br>
Provide the link for the page related to Speaker Demographics if available.<br><input type="text" id="sdlink" name="sdlink"><br><br>
</p>

<h2>Attendee Demographics</h2>
<input type="checkbox" id="adcb">This event commits to Attendee Diversity & Inclusion.
<p>  
Detail the process for measuring Attendee Demographics.<br><input type="text" id="addsc" name="addsc"><br><br>
Provide the link for the page related to Attendee Demographics if available.<br><input type="text" id="adlink" name="adlink"><br><br>
</p>

<h2>Code of Conduct at Event</h2>
<input type="checkbox" id="coccb">This event commits to the Code of Conduct at Event.
<p>  
Is the code of conduct posted at Event venue?<br><input type="text" id="coclink" name="coclink"><br><br>
Provide the link for the Event Code of Conduct.<br><input type="text" id="cocdsc" name="cocdsc"><br><br>
</p>

<h2>Diversity Access Tickets</h2>
<input type="checkbox" id="dtcb">This event commits to the Diversity Access Tickets.
<p>  
How many different types of diversity access tickets are available for the event?<br><input type="text" id="dt2" name="dt2"><br><br>
What are the criteria for qualifying for a diversity access ticket?<br><input type="text" id="dt3" name="dt3"><br><br>
Provide a link to the page containing information about Diversity Access Tickets.<br><input type="text" id="dt1" name="dt1"><br><br>
</p>

<h2>Family Friendliness</h2>
<input type="checkbox" id="ffcb">This event commits to Family Friendliness.
<p>  
Does the Event provide childcare facilities for its attendees and speakers?<br><input type="text" id="ff1" name="ff1"><br><br>
What are the other ways that a family-friendly environment is being created in the Event?<br><input type="text" id="ff2" name="ff2"><br><br>
Provide relevant links related to family friendliness at the Event.<br><input type="text" id="ff3" name="ff3"><br><br>
</p>
</div>
<div id="end">

</div>
<div id="template" style="display:none">
    # Event Submission

    ## Requirements
    
    - Project Name: {pname}
    - Link to the Event Website: {linkweb}
    
    ## Speaker Demographics
    
    - [{sdcb}] This event commits to Speaker Diversity and Inclusion.
      - `Q` Detail the process for measuring Speaker Demographics.
      - `A` {sddsc}
      - `Q` Provide the link for the page related to Speaker Demographics if available.
      - `A` {sdlink}
    
    ## Attendee Demographics
    
    - [{adcb}] This event commits to Attendee Diversity and Inclusion.
      - `Q` Detail the process for measuring Attendee Demographics.
      - `A` {addsc}
      - `Q` Provide the link for the page related to Attendee Demographics if available.
      - `A` {adlink}
    
    ## Code of Conduct at Event
    
    - [{coccb}] This event commits to the Code of Conduct at Event.
      - `Q` Is the code of conduct posted at Event venue?
      - `A` {coclink}
      - `Q` Provide a link for the Event Code of Conduct.
      - `A` {cocdsc}
    
    ## Diversity Access Tickets
    
    - [{dtcb}] This event commits to the Diversity Access Tickets.
      - `Q` How many different types of diversity access tickets are available for the event?
      - `A` {dt2}
      - `Q` What are the criteria for qualifying for a diversity access ticket?
      - `A` {dt3}
      - `Q` Provide a link to the page containing information about Diversity Access Tickets.
      - `A` {dt1}
    
    ## Family Friendliness
    
    - [{ffcb}] This event commits to Family Friendliness.
      - `Q` Does the Event provide childcare facilities for its attendees and speakers?
      - `A` {ff1}
      - `Q` What are the other ways that a family-friendly environment is being created in the Event?
      - `A` {ff2}
      - `Q` Provide relevant links related to family friendliness at the Event.
      - `A` {ff3}    
</div>
<input id="fsub" type="submit" value="Submit">
<input id="fback" type="submit" value="Go Back" style="display:none">
<script src="./main.js"></script>

</body>
</html>