# Build a Web Scraper with Node.js - IMDB Movie Search

View the video [here](https://www.youtube.com/watch?v=U0btOGPwrIY)

> The video references [pollly](https://poll.ly/#/) as Platform on which video
> suggestions can be made. This is **OUTDATED**. Please use 
> <https://poll.coding.garden/>.

## Outline

- [1:12] Introduction
- Set up server folder
  - [3:42] initilize a node app
  - [3:57] npm install node-fetch
  - [4:26] How to use node-fetch
- Parsing HTML with cheerio
  - [6:49] Overview of cheerio
  - [7:18] Add cheerio to server code
  - [7:39] Get movie titles and movie posters from IMDB search :tada:
- Start using express
  - [11:53] Format data as JSON
  - [13:04] Prepare code for modularity
  - [14:12] Create a basic express app
  - [15:39] Create node scripts (auto-reload with nodemon)
- Building an API in express
  - [16:31] Create search route
  - [18:02] Get movie id from IMDB
  - [20:12] Create movie route
  - [23:19] Get data from IMDB movie page
    - [23:25] Title
    - [26:39] MPAA Rating
    - [27:59] Run time
    - [29:58] Genres
    - [31:45] Release date
    - [32:50] IMDB rating
    - [33:40] Movie poster
    - [37:04] Summary
    - [38:03] Directors
    - [43:24] Writers
    - [46:52] Actors
    - [49:32] Story line
  - [51:50] Things to keep in mind when scraping the web
  - [53:10] Back to getting data from IMDB
    - [53:10] Try getting budget
    - [54:09] Production companies
    - [57:46] Link to trailer (Part I)
  - [1:00:49] This is OUTDATED. Please use https://poll.coding.garden/
  - [1:01:21] Link to trailer (Part II)
  - [1:03:40] Add caching
  - [1:07:16] Deployment via now
- Create Frontend in Vanilla JS
  - [1:09:45] Add CORS to server code
  - [1:11:11] Create client folder
  - [1:11:42] Add Bootswatch CDN
  - [1:12:21] Start styling 
  - [1:15:50] Add search logic
  - [1:18:58] Show search results on page
  - [1:23:04] Create movie page
  - [1:41:52] Format date with date-fns
- [1:46:04] Review of what we have built today!
- [1:51:42] This is OUTDATED. Please use https://poll.coding.garden/

Contributed by: @sbibow
