# notepad_with_sqlite3
This an educational `Ruby` application - improved notepad with `sqlite3` data storage.

To start using this application, you have to have
```
ruby
sqlite library
```
installed on your local machine.

You can clone this repo onto your local machine, make `cd` in the directory and, first of all, 
you have to create `notepad.sqlite` database in the project dir with `SQLite manager` or other tool you would
like to use. You can change the database name if you like, it is hardcoded in `lib/post.rb`, just change the value of
`SQLITE_DB_FILE` constant.

After creating the database you can start the application in `write-mode`. In your local app dir, run
```
ruby new_post.rb
```
Then you have to choose post type you would like to create: memo, task or link.

As for `memo`, it is just a note which may consist of several strings. When you're done writing your memo,
just input `end` on new line. Your memo will be saved.

Here is the memo example:

![alt text](https://media.giphy.com/media/XqHMcQtdY16234dSeo/giphy.gif)

Furthermore, you may create `task`. It is just your average 'to-do-list' with 'due-date' field. Just enter your
task and date you want to accomplish this.

Here it is:

![alt text](https://media.giphy.com/media/ZmPbHQpQ6EPIl8RUXs/giphy.gif)

Finally, there is a `link` option. Choose it if you want to save some link. Don't forget to enter the description!

Look at it, it is pretty awesome, isn't it:

![alt text](https://media.giphy.com/media/jdTZQynWmfgERqzP6m/giphy.gif)

To read all your data, just run the application in `read-mode`. In your local app dir, run
```
ruby read.rb
```
and get all the notes you've added.

![alt text](https://media.giphy.com/media/ta20YtL2b97a430yGj/giphy.gif)

Hope you will enjoy my app.
