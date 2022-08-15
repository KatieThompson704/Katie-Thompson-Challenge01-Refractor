# Katie's Code Refactor - Challenge 01

## Description

The purpose of this project is to refactor HTML and CSS starter code to meet accessibility standards. The starter code modifications were made using objectives defined in the following User Story and Acceptance Criteria.

### User Story

AS A marketing agency <br>
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

### Acceptance Criteria

GIVEN a webpage meets accessibility standards
 - WHEN I view the source code <br>
 THEN I find semantic HTML elements<br>
 - WHEN I view the structure of the HTML elements<br>
THEN I find that the elements follow a logical structure independent of styling and positioning<br>
 - WHEN I view the image elements<br>
THEN I find accessible alt attributes<br>
 - WHEN I view the heading attributes<br>
THEN they fall in sequential order<br>
 - WHEN I view the title element<br>
THEN I find a concise, descriptive title<br>
 
## Summary of Changes 

The following modifications were made to the code with asssociated comments:

- Replaced nonsemantic HTML elements, icluding div, with semantic HTML elements, such as header, section, footer, etc. Then, updated CSS file to match
- Replaced HTML title element "website" with concise, descriptive title
- Added alt attributes to img elements to bring them up to accessibility standards
- Updated heading attributes in HTML to ensure sequential ordering
- Consolidated CSS styling when possible

## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```