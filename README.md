# Budget Tracker
# Description
 
- This application is a fully functioning budget tracker that allows you to to add and subtract expenses on and offline.

- If the internet or network for some reason goes out then the user has the ability to see post that he or she has already create along with adding more, this is all because of IndexedDB.

- Since there is a IndexedDB in place the the application does not need the local MongoDB database to save data that the user has posted. Instead the data that has been posted is stored in the IndexedDB on the DOM so when the internet connection comes back online the user post is still there.

- The user has the opportunity to add and subtract items that are updated on a graph provided by graph.js.

- With all of these features combined the user has a fully functioning budget tracker off and online.
# Features
- Mongoose
- Express
- Compression
- Morgan
- IndexedDB
- Manifest.webmanifest file 
- Service workers

# Demo

![](budgetgif.gif)
# Usage

- Both back and front end databases with IndexedDB and MongoDB

- User can post data offline and see it when it comes back online

- Chart.js gives a great visual of you recent purchases
# License
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Copyright (c) [2021] [Dawan Sawyer]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.