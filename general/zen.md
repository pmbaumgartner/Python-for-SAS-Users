###
As a compliment to this project, it may be helpful to review the [Zen of Python](https://www.python.org/dev/peps/pep-0020/) in order to understand why Python and its packages won't be exactly the same as SAS, but with good reason. The Zen of Python can help us illuminate some of these differences.

You can view this at any time by doing `import this` in a Python Program.

Let's review the aphorisms and talk about SAS.

1. Beautiful is better than ugly.  
Since Python is a general programming language, most features of the SAS Macro language are built in and are a lot easier to use once you understand basic [control features](https://docs.python.org/2/tutorial/controlflow.html). No  ugly `%`, `&`, or weird escaping with periods. Plus Python's indentation will force you write programs without getting lost within macro loops.

2. Explicit is better than implicit.  
SAS gives you *everything* on output. `PROC UNIVARIATE` outputs a t-test for example. Did you ask for a t-test? This aphorism is related to the next one, *Simple is better than complex*, in the sense that you'll only typically get what you ask for with Python. The explicit nature gives you more control over what you see.

3. Simple is better than complicated.  
Again, SAS output can be complicated, leaving the user searching for the one line of output they need. Also similar to *Beautiful is better than ugly* since the SAS Macro language can leave someone exhausted after figuring out [how all those ampersands resolve](http://stackoverflow.com/questions/22903856/sas-macro-ampersand). 

4. Complex is better than complicated.  


5. Flat is better than nested.  

6. Sparse is better than dense.  
7. Readability counts.  
I'm looking at you, SAS Macro Language.

8. Special cases aren't special enough to break the rules.  

9. Although practicality beats purity.  


10. Errors should never pass silently.  
11. Unless explicitly silenced.  
12. In the face of ambiguity, refuse the temptation to guess.  
13. There should be one-- and preferably only one --obvious way to do it.  
14. Although that way may not be obvious at first unless you're Dutch.  
15. Now is better than never.  
16. Although never is often better than *right* now.  
17. If the implementation is hard to explain, it's a bad idea.  
18. If the implementation is easy to explain, it may be a good idea.  
19 Namespaces are one honking great idea -- let's do more of those!  
