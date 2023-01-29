# LinkShortener
Link shortener made using django

This is a URL shortener built using the Django web framework. It utilizes the Django ORM to interact with the database and the `ShortenUrl` model to store shortened URLs. The code uses the redirect view to redirect the user to the original URL when they visit the shortened URL. The create view is used to create new shortened URLs, which are generated using a random alphabetic string of length 6. The codes view displays a list of all shortened URLs stored in the database. The `createRandom()` function is used to generate the random alphabetic strings for the shortened URLs. The code also uses the messages framework to display success and error messages to the user.

This HTML code is for a webpage that serves as a URL shortener. It uses the Django framework and includes some elements of Bootstrap for styling. The page displays a form where users can enter a long URL and an optional custom name for the shortened link. When the form is submitted, the code checks for any messages that were passed in from the backend, which can include a success message with the shortened link or an error message if there was a problem with the input. If there are no messages, the form is displayed as usual.
The page also lists all of the previously shortened URLs, including the original link, custom name (if any), shortened link, and a button to copy the shortened link to the clipboard. The HTML also has some JavaScript code to handle the functionality of the "Copy" buttons.
