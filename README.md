<?php$response = file_get_contents('https://api.example.com/data');if
($response === FALSE) { // Handle error echo "Failed to retrieve
data.";} else { echo $response;}?>
