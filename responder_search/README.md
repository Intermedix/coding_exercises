# Responder Search

This exercise focuses on JavaScript, AJAX, and some PHP (but you're
free to choose a different backend language if you want).  We
provided a JavaScript file that fetches all responders and loads them
into the table immediately after the page loads.  We also provided a
minimal PHP class to provide the responder data. 

However, the search bar and table filters haven't been implemented
yet.  Your goal is to modify the JavaScript and/or backend in order
to get the table to refresh on the fly as the user changes the
textbox and dropdown values.

## Testing

In addition to the application itself, there is a test.html file
which loads QUnit and runs two JavaScript unit tests.  If you haven't
written unit tests before, they're a great way to automate testing
and prevent bugs being introduced.

The first test in js/test.js checks that the App JavaScript loaded,
and the second is for you to fill in.  Try to write a simple test or
two to verify the things you implement work as expected.

## License

Copyright 2014 Intermedix Corporation.
 
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
 
    http://www.apache.org/licenses/LICENSE-2.0
 
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
implied.  See the License for the specific language governing
permissions and limitations under the License.
