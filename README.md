# py_playground

So this is pretty much me just messing around with python

Overtime I hope to add more and more app to this but so far this is what I have:
- Instagram Account searcher
  - They way it works is by scraping the web for your data by passing your username through the link, really, really simple.
- Instagram user collector
  - what this does is searches a tag and then scrapes the webpage for usernames and adds it to the collection
## Todo's:
- [ ] Feed the list of the usernames that are collected to the account searcher
- [ ] take data from the account searcher and admit them to the database
  - not sure how i'm going to do this
- [ ] make a database
- [ ] make a scheduler for the database
- [ ] create restful api to use the data
- [ ] setup vm in google or azure (which ever will be the cheapest tbh)

### Setup:
1. First make sure that you have pip and pipenv installed on your machine
2. Use command ```$ pipenv install ```  <- this will automatically start installing all the required packages for this app to run
3. Once installation has finished, go ahead and use what ever method you prefer to use edit/ run your python app. I prefer going into the shell and do what I have to do that way via: ```$ pipenv shell ``` and then ```$ python main.py ```
4. And that's it! Happy Instagraming!!!!!

------------------------------------------------------------------------------------------------------------------------------------------

If any issues occur just hit me up and let me know, I'll figure it out, or do a pull request if you figured it out
