# hacker-news-reader
Simple Android application that uses the Hacker News API to display articles.

Parses JSON from the Hacker News API, stores article information in a SQLite database, and populates a listview using the information.
Users can then click any item in the listview to open a new activity with a webview that displays the article.
The SQLite database allows seeing the list of articles offline.
