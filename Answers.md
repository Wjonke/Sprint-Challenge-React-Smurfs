1.  Explain the differences between `client-side routing` and `server-side routing`.

Client side routing is done by the Javascript that is loaded by the page, when the url changes, so does the diplayed information and state of the application, without sending a server request. The whole page will not refresh when using client side, only the components that changed. The whole app is loaded when first rendered, a little longer initial loading. Optimized for large volumes of changing data to be displayed and changed without having to reload the page.

Serverside Routing will request a whole new page to be rendered when a link is clicked, pages are loaded as needed, spreading a load time out for every request.
Serverside is better for search engine optimization, but everytime you need new data when entire page refreshes from the get request. Its not efficient for large volumes of quickly changing data.



1.  What does HTTP stand for?

HyperText Transfer Protocol



1.  What does CRUD stand for?

create, read, update and delete



1.  Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.

GET, POST, PUT, DELETE



1.  Mention three tools we can use to make AJAX requests

Axios, Fetch, JQuery