# Coding Challenge - maxdome
---


### Functional Requirements:

You will need an API key for the the Pixabay public web services. It can be retrieved from this page (you must be logged in to see it): [Pixabay API](https://pixabay.com/api/docs/#api_search_images)

The user should be able to search for images entering one or more words in a text field
Request the Pixabay API to show the images associated with the text provided by the user and parse the JSON response.

Display a list of results. Each entry should show:
* A thumbnail of the image
* The Pixabay user name
* A list of image’s tag Cache the response
* With a press on a list item a detail screen is opened.

The detail screen should contain:
* A bigger version of the image The name of the user
* A list of image’s tag
* The number of likes
* The number of favorites
* The number of comments

When the app starts it should trigger a search for the string “cats”
If you have any final comments about your result please let us know creating a file called README.md inside the root directory of the project.
For bonus points demonstrate an understanding of how you would test your code.

### Technical Requirements:
* Language: Objective-C
* Storyboard with Size Classes and Auto Layout
* Xcode 8.x
* iOS 10.x
* iPhone SE/7 with support for Landscape and Portrait You may use 3rd-party libraries
* You are free to use dependency management tools
* Drive the implementation with tests. If so your test cases must clearly state what you are testing and what the expected results are, they must be legible, easily understandable and to the point. Speci$
* Provide a new user interface where you can show a list of the results you got from a request.
* Add pagination for new user interface of the list of results. So that when the user scrolls to the end of the collection view / table view, then it loads more search results.

### Evaluation Criteria
* You care about user experience.
* You build user interfaces with the Human Interface Guidelines in mind.
* You write code that is efficient, readable and follows best practices (like decoupled, single responsibility principle, etc).
* You know how to keep the UI responsive.
