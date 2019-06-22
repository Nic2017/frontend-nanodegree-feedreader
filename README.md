# frontend-nanodegree-feedreader  
## Project Overview  
This project is a web-based application that reads RSS feeds. It mainly uses Jasmine to make testing for Javascript code.  
## Testing Suites  
1. **RSS Feeds**: It tests to make sure that the allFeeds variable, URL and name have been defined and that it is not empty.  

2. **The menu**:  It ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element. It also ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.  

3. **Initial Entries**: It ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.  

## How to Run  
Clone the repository to your local computer. Open file index.html in browser. The testing results will be displayed at the bottom of the page.
