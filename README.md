# Consumables_Template
This is demonstration code for working with the consumables framework in Volunteer Science.

To make this work, you must create a class of consumables in your "Manage Consumables" tab and create a set of consumables within the class.

For example, say you have 10 statements you want people to code as positive or negative. You create a class called whatever, say "Affect Statements." Once you create the class, add your 10 statements, one per row, in the editor or copy them from a file like Excel and save. 

Then, you can check each statement to enable or disable them individually or check a bunch, type a name like "first set" into the box and click "New Set".

Then in the consume.js file, change "consumeDemo" and 'set1' to the class and set names you used (here: "Affect Statements" and "first set").
