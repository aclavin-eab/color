How to use
=====
Use the jquery.randomcolor.cs by entering the following after your jquery library

    <script type="text/javascript" src="jquery.randomcolor.js"></script>

Use the function 

    $('selector').smoothChange(); 
    
to use the color randomize on an object.

Options
===============================

    $('selector').smoothChange({
        range: 10,
        scale: 2,
        red: off,
        blue: 2,
        green: on
    });
    
Range (default 5) will add a number of steps to the color change.

Scale (default 0) will increase the range of the color steps.

Red (default on) will either; (off) prevent the red channel from changing, (on) allow it to change, (number) multiply the channel to cause it to change more than the others.

Green/Blue (defaults on) will do the same as red for their respective channels.

