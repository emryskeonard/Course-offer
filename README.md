# Course-offer

<?php

// List of courses
$courses = array("COM411", "COM414", "COM412", "COM413", "COM415", "EED");

// Assigning scores to each course
$scores = array();
foreach ($courses as $course) {
    // Generate a random score between 0 and 100 for each course
    $score = rand(0, 100);
    
    // Assign the score to the course
    $scores[$course] = $score;
}

// Displaying the scores for each course
foreach ($scores as $course => $score) {
    echo "$course: $score\n";
}
?>
