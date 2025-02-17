# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```

## Accessibility Lab Answers

Color: 
    To help with the color contrast, I tested each of the colors' contrast ratio with one another. I saw that the preferred ratio is 7. I found that the black font on the green background was 2.79, so I changed the green to a lighter pink which was 9.33. Since the header had black shadowing, I felt as though that was fine. The comment box was at 10.67, so I left that as well. 

Semantic HTML: 
    The tab key makes it move through the different options on the screen, and you can scroll with the spacebar. For the article, I separated the text into sections, formed the text into paragraphs instead of line breaks, and assigned each of the titles as different headings. For the navigation bar, I used a nav wrapper instead of putting the navigation bar into a div. 

Images: 
    I added descriptive alt text for both of the photos. 

Audio Player: 
    For the audios, I tried adding captions, but mainly I added a transcript for the audio that could be accessed. I added a label for the audio and then a fallback with a link to the audio for older browsers. 

Forms: 
    I added a label for the search query and put it in a class that clarifies that it is only meant for the screen reader. Then I added CSS for that class in the typography section so that it is hidden. I added two labels for the name and the comment for each person's comment. I used the CSS to display it accordingly. 

Show/Hide Comment Control: 
    For the comment section, I added tabIndex=0 so that you could focus using the tab button. I added a keydown event to allow for the comments to toggled based on the enter key.  

Table: 
    For the table, I added a descriptive summary of the table and table headers for each of the columns. I tried to incorporate the proper scope for the columns as well. 

