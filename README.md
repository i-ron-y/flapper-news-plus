# Flapper News Plus

Modified version of Flapper News (from the [Learn to Build Modern Web Apps with MEAN -- Thinkster](https://thinkster.io/tutorials/mean-stack) tutorial).

## Modifications

##### Suggested at the end of the tutorial:

* Implement downvoting for posts and comments.
* Display number of comments for each post on main page.
* Implement button to show/hide 'new post' and 'new comment' forms.
* 

##### Personal ideas:

*

## Usage

If you don't have MongoDB yet, download and install MongoDB.

Create the following folders in the MongoDB directory (e.g., `C:\Program Files\MongoDB\`):
	* `data`
	* `data\db`
	* `log`

Go to the `bin` directory.
<br />(e.g., `C:\Program Files\MongoDB\Server\3.4\bin`)

Run `.\mongod --port 27017 --dbpath "[MongoDB directory]\data\db"`.
<br />(e.g., `.\mongod --port 27017 --dbpath "C:\Program Files\MongoDB\data\db"`)

Go to the `flapper-news-plus` directory.

Install the required packages:

````
npm install
````

Start the app:

````
npm start
````

Your app should now be accessible at http://localhost:3000.

## Credits

[Learn to Build Modern Web Apps with MEAN -- Thinkster](https://thinkster.io/tutorials/mean-stack)