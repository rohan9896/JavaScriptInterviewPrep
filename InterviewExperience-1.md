 # Company name - Project-tinker #
 ## Role - React Developer ##
 # Round-1: #
20 min dicusssion with founder and a take home project(1 week time).

Assignment:

Problem Statement
Design a Library System to be used by a Librarian to maintain information regarding Authors and their Books.

## Specifics ##
### Authentication ###
* A Librarian can log in using email/password
* A Librarian can signup with their Name, Email, Phone Number and Password
* Authors Management (Logged in users only)
* All authors can be viewed in a list or grid view with relevant information. (Pagination is an optional bonus). Authors can be added, edited or deleted from this page. Please note Author's books must be deleted before deleting the Author.
* On clicking on a particular card, the user is taken to the Author page. The Author page displays the author's information as well as information related to all the books written by the author (Clicking on a book card takes the user to the Book Page)
* Books Management (Logged in users only)
* All books can be viewed in a list or grid view with relevant information. (Pagination is an optional bonus). Books can be added, edited, or deleted from this page. Please note a valid ISBN needs to be provided to create a book. The ISBN can be validated using regular expressions.
* On clicking on a particular card, the user is taken to the Book page. The Book page displays the book's information as well as information related to all the authors of the book (Clicking on an author card takes the user to the Author Page)

You are free to make suitable assumptions related to the user, author, and book information.

### Implementation details ###
* The backend can be built using ExpressJs and Mongo or using Firebase (Recommended for faster prototyping) or any other framework of your choice. Alternatively, an in-memory database can be used in the React App in the event of insufficient time to complete the assignment.
* The React application must have a simple, responsive UI styled well.
* Usage of libraries like react-helmet, material-UI is recommended.
* Usage of advanced state management libraries (Redux, Saga, etc) is not necessary however usage of React Hooks and if necessary React Context is expected.
* Points of evaluation (Order of importance):
* Frontend User Interface
* Design of models and service layers on the React app
* Handling of edge cases, invalid and incomplete input.
* Handling edge cases like error responses, network failure etc. on the React app.
* Frontend and Backend Authentication flow
* Database modeling
* Backend Security
* Wherever possible and applicable, justify your design choices as comments.

https://library-management-develop.web.app/


# Round 2 #

Q1. You have implemented authentication in your project, can explain how it works?

Q2A. As I am able to see in the networks tab, you are calling all 100 peoducts in your ecommerce project at once. What can you do to optimize it?
--> Pagination

Q2B.(Follow up) Explain how pagination works?

Q3. You have mentioned Data Structures and algorithms in your resume! Are you comfortable in solving one question?
--> Then asks me to code median of two sorted array problem in a google doc.

Q4. How does Event Loop works?

Q5. How to do caching in websites?
--> He wanted to listen about http caching, but as i didnt know about that so i explained him that if we are building website using react we can use useMemo hook to memoize the function calls.

Q6. Explain HTTP? (he asked me this bcoz i have written a blog on this)

Q7. Discussion on all three projects.(E-Comm, video library, component library)

Q8. What is CSR and SSR?

Q9. How does useEffect Hook works? Is it synchronous or asynchronous?

### Final Verdict - REJECTED ###
