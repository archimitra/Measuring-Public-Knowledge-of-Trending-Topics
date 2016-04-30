# Overview :
What do we do when a friend asks us if we have heard about this topic which went 'viral'? We
feel like a fool that we don't know about it and immediately Google it and click on the first link
which most often than not is a Wikipedia page. This is just a theory. The objective of this
project is to mine, clean and store data which can be used to support, validate and further this
theory.

## Phase 1: Trending Topic
The Twitter RESTful API is used to find the top 50 current trending topics. The #Hashtag or
the ‘Trending Topic’ gathered is then used to create a searchable item to be used in the next
phase.

## Phase 2: Wikipedia Article Search
The WIkipedia Opensearch API is an open source project which can be used to find articles in
Wikipedia. This is used to search the ‘searchable item’ created in the last phae to find the
relevant articles.

## Phase 3: Article View Count
The MediaWiki API provides a very useful ‘pageview’ programmable URL. The page view count
for articles found in Phase 2 is mined using this.

Please refer to the .pdf file for a detailed report on the project. Also, the Project Comment.txt has all the instructions on how to use the R Script.
