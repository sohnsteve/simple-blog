# simple-blog

This is a node server passing html via ejs.  Ejs files allow JavaScript embedding to show dynamic content.  A user aware of the specific URL to post, in this case: <hostname>:<port>/spidermake (yes... "spidermake"... my prerogative) which will show a compose page.  It then generates a new blog page and adds a summary of the content on the home page.  The home page, then, will show a list of all the posts saved showing only a concatenated version.  Visitors may then see the full blog post by clicking the "see more" link.
  
Post title and content are saved/persisted on MongoDB.
