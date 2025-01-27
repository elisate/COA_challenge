# COA_challenge
# COA_challenge

1.UI-challenge Decription
-------------------------
This project is a responsive image gallery that works seamlessly on both desktop and mobile devices. It includes features such as image thumbnail navigation, full-size image viewing, and various interactions as specified in the designs.

Project Structure
The project is organized into the following directories:

assets: Contains all the images used in the gallery.
css: Contains all the stylesheets for the project.
js: Contains all the JavaScript files for the project.
index.html: The main HTML file that contains the structure and layout of the gallery.
Features
Responsive Design: The gallery layout adapts to different screen sizes to ensure a seamless experience on both desktop and mobile devices.
Image Thumbnail Navigation: Users can navigate through images using thumbnails.
Full-Size Image Viewing: Clicking on a thumbnail opens the full-size image.
Interactive Elements: Additional interactions as specified in the designs.
Setup and Usage
Prerequisites
Ensure you have a web browser installed. No additional software is required.

2.Coding Challanges
----------------------
-----2.1.String Transform-----

this file contains stringTransform function, which performs specific transformations on a given string based on its length. Additionally, it outlines a set of test cases to verify the function's correctness.

Function Description
stringTransform(input)
The stringTransform function takes a single argument, input, which is a string. The function transforms the string based on the following rules:

If the length of the string is divisible by 3, the string is reversed.
If the length of the string is divisible by 5, each character in the string is converted to its ASCII code, and the codes are joined by spaces.
The transformations are applied sequentially, meaning that if a string's length is both divisible by 3 and 5, it will be reversed first, and then each character in the reversed string will be converted to its ASCII code.

Parameters:
input (string): The string to be transformed.
Returns:
transformed (string): The transformed string after applying the relevant rules.

-----2.2.Array Map-----


this file contains  subarray function, which checks for the existence of a contiguous subarray within a given array that sums to a specified target. It also includes a framework for testing the function.

Function Description
subarray(arr, target)
The function determines if a contiguous subarray in arr sums to target using a sliding window approach.

Parameters:
arr (array): Input array of integers.
target (number): Target sum.
Returns:
boolean: true if a contiguous subarray sums to target, otherwise false.

