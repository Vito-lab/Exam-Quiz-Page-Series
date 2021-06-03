# Exam-Quiz-Page-Series

Here is the Quiz / Exam Test page for PC desktop width. It contains: HTML:

    6 radio button questions;
    4 checkbox questions;
    20 open questions with dropdown selections, input text boxes;
    icons for quick navigation for each question and Submit buttons / Results;
    separate submit buttons for radio & checkbox questions and for open questions;
    Support windows and navigation icons for them.

JS:

    first submit button opens title of open questions, open questions and 2nd submit button, closes quiz / test part questions;
    first submit button shows result of quiz / test part;
    first submit button gives green/red colors on correct/incorrect answers of exam test part;
    first submit button gives green/red/orange colors on navigation icons for each question depending on correct/incorrect/partially correct answers;
    first submit button opens open questions' navigation icons, closes test part questions' navigation icons;
    first submit button makes all quiz / test part questions disabled;
    second submit button opens title of quiz / test questions, quiz / test part questions, navigation icons of test part questions;
    second submit button gives green/red/orange colors on navigation icons for each question depending on correct/incorrect/partially correct answers;
    second submit button makes open questions readonly and dropdowns disabled;
    quiz / test part questions are worth points. When 1st submit button is pressed, the test score is shown;
    test score is shown only if all radio questions are checked. Otherwise alert message is given;
    open questions' dropdowns show images or do other action when selected;
    open questions are also worth points. Their points are converted to open score with scale 0-10;
    test score and open score forms final score where test score is worth 30% of final score and open score is worth 70% of final score; 
    input text box gives command to write the same text in other input text box in open question. Text visibility is regulated with different fonts and letter space;
    open score result contains "details button" which when clicked shows detailed explanation for what points were given in open questions plus total points collected from each question;
    navigation icons when are clicked scrolls into view their appropriate questions;
    all values are reseted when page is refreshed or appropriate analogic option is selected;
    some more minor codes which makes the experience of this page's usage pleasant.
    
    
EDIT (exam Nr.2 and later):

    improved CSS for page color shadows. Now all code lines of page color shadows are in 1 CSS file as commented (optional) code.


EDIT (exam Nr.3 and later):

    added Toon Mechanic in Open Tasks' Mechanic options;
    added Effect text visibility in card's image; 
    added lowercase/uppercase insensibility in "assessorsOpen" folder's files when assessing values of Open Tasks' Effect fields;
    added Music with button to mute and unmute it;
    added "Go back to top" button;
    added Result Details of Test Questions button with Test details window and info;
    added Hover text on Navigation icons and Result Details' icons;
    added page color changes with CSS and JS;
    added screen width adjustions;
    added font awesome icons in Info and Help support icons' slots and therefore Info and Help picture icons were removed;
    improved CSS for page colors. Now all code lines of page colors are in 1 CSS file;
    improved Info and Help windows' closure features. Now these windows will close only when user clicks mouse left-click outside window. Also improved scrolling features in the window's field;
    improved background picture's scaling. Now proportions of picture do not change while changing screen size;
    code was shortened (was 388 JS files, now 302). Created dependencies on parent functions for simplier editing.
