# _spotify-pandas_

#### By _**Alejandro Socarras**_

#### _Week 4 Code Review_

## Description

_Assignment Instructions_

**Profiling**
* For each dataset, profile the data using head(), tail(), and .shape(). Write a comment for each one, briefly explaining what this technique does, and what the output you got tells you about the dataset.

* For Albums, use .loc or iloc to show just rows 10-20 of the 'name' and 'release_date' columns

**Cleaning and normalizing**

* Remove duplicates from each dataset

* For Artists:

    - Write a map() function to replace the empty list ([]) entries in the genres column with NaNs (but don't alter the list entries in genres that contain values!)

* For Tracks:

    - Print the names of the columns in Tracks

    - First, look at the values for lyrics to see why you think they don't parse well in Excel and some other programs

    - Drop the lyrics column

    - Print the names of the Tracks columns again, to show that the 'lyrics' column has been dropped
  
**Joining**

*  Using Pandas, perform the following joins, choosing the join type that you think is appropriate. Make a comment in your code file on why you chose that join type.

    - Join artists and albums on the artist ID. Print the head() and shape of the resulting DataFrame.

    - Join albums and tracks on the album ID. Print the head() and shape of the resulting DataFrame.

**Analyzing**

* Use Pandas to calculate the following statistics on the data, and print the results:

    - Which artists appear the most times in the Artists data?

    - Which artists have the highest 'artist_popularity' rankings? (list the top ten in descending order)

## Setup/Installation Requirements

_To run the project from your local system:_

1. Make a directory on your disk where you would like to clone the repo.

2. Copy the repo link: https://github.com/apsocarras/spotify-pandas.git (available if you click the green "Code" dropdown button on this page).

3. Open your terminal and change into the directory you made (`cd /path/to/new/directory`).

4. Type `git clone ` and paste the URL.

## Known Bugs

_No known bugs._

## License

_[MIT License](https://opensource.org/licenses/MIT)_

Copyright (c) _12.2.22_ Alejandro Socarras

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
