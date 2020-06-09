# planner

Aim to create a daily planner

Break into parts for easy tackling.

-input user data into timeblock
-save user data to local storage
-date and time using js momentum
-timeblocks- 8am to 6pm
-colour coding the times - past, present and future

pseudocode

preparation
-add js to script tag 
-add jquery to script tag
-download and add moment.js to script tag
-link css
-document ready function

html
-header div class time
    title- work schedle
    current day, date, month and year
-container div/section
    divs/spans -11 hour day 8am to 6pm
    save button on right side
    time on left side
-scroll ability?

1. create time blocks -11
    -create a variable that calls the div section 
    var timeblocks = container div

    -use forms to input data
    add 11 forms for the different time spot 
    (loops?)/ add individually
    use label from bootstrap 

    -add a button to the form to save data
    (form).append button

    -add a space for the time
    (form).append
    (form).insert after

2. input from user
    .text content or innerhtml

3. save button
    -event click function
    (button).on click
    -prevent default, loading page
    -save to local storage
    -local storage. set item .JSNstringify

4. create header and time
    -add title like scheduler

    -create var - attched to header = schedule
    $(shedule )


    -sub title todays events
         $(shedule ).text
   
    -use momment().format dddd mm yyyy; to log current day and time

5. time factor 

    -using moment.js to create dynamic times 
    const start = moment().startOf('day'); or maybe hour

    
    - if time is passed change to different colour

    default colour function
    .css style

    present colour function
    if current time (hour) change to red
    moment.is same as
    moment().isSame(Moment|String|Number|Date|Array);

    past colour function
    if current time not 
    change to grey
    moment is after
    moment().isAfter(Moment|String|Number|Date|Array);

6. scroll
 $( window ).scroll();
});


    








