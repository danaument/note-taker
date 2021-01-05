# Title: Note Taker

## Table of Contents:
* [Description](#Description)
* [Installation](#Installation)
* [Usage](#Usage)
* [Deployed Project Location](#location)
* [Notes from Dan](#Notes)
* [Credits](#Credits)
* [License](#License)

### <a name="Description">Description:</a>
This application is a homework assignment for UT's web dev coding bootcamp.  It uses the express.js and a JSON database file to store notes.  

### <a name="Installation">Installation:</a>
The application's dependencies can be installed using the following command in the directory containing the files, including the package.json file: 

```bash
npm i
```

### <a name="Usage">Usage:</a>
The application can be invoked using the following command: 

```bash
node server.js
```

The user can input notes with a title and body 

### <a name="location">Deployed Project Location: </a>
https://damp-cove-32933.herokuapp.com/ 

Please note that Heroku will automatically "forget" any saved notes after a period of time, since this is the free version of their hosting service.


### <a name="Notes">Notes from Dan:  </a>
I found this assignment to be very brief, which I appreciated because I had to work on it over the holidays.  The one item that I found a bit confusing was using 'require' to read the JSON file, when all of our previous activities had used fs.readFile, etc.  I had difficulty getting the front end to refresh the list of saved notes until I realized that I wasn't sending a response from my server on the DELETE function.  Of course!  How can the front end know to move on without a response?

### <a name="Credits">Credits: </a>
This project was completed by Dan Aument using code and assets provided by The Coding Boot Camp at UT Austin in partnership with Trilogy Education Services. 

### <a name="License">License: </a>

Distributed under the MIT License

MIT License

Copyright (c) 2020 Daniel Aument

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