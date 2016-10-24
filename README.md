#Python Data Science Essentials - Second Edition
This is the code repository for [Python Data Science Essentials - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/python-data-science-essentials-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786462138), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.
##Instructions and Navigations
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The appendix of this book doesn't have any code files.

Python and all the data science tools mentioned in the book, from IPython to Scikit-learn, are free of charge and can be  freely downloaded from the Internet. To run the code that accompanies the book, you need a computer that uses Windows, Linux, or Mac OS operating systems. The book will introduce you step-by-step to the process of installing the Python interpreter and all the tools and data that you need to run the examples.

The code will look like the following:
```
File: bottle1.py
from bottle import route, run, template
port = 9099
@route('/personal/<name>')
def homepage(name):
return template('Hi <b>{{name}}</b>!', name=name)
print("Try going to http://localhost:{}/personal/Tom".format(port))
print("Try going to http://localhost:{}/personal/Carl".format(port))
run(host='localhost', port=port)
```

Python and all the data science tools mentioned in the book, from IPython to Scikit-learn, are free of charge and can be freely downloaded from the Internet. To run the code that accompanies the book, you need a computer that uses Windows, Linux, or Mac OS operating systems. The book will introduce you step-by-step to the process of installing the Python interpreter and all the tools and data that you need to run the examples.

##Related Products
* [Expert Python Programming](https://www.packtpub.com/application-development/expert-python-programming?utm_source=github&utm_medium=repository&utm_campaign=9781847194947)

* [Practical Data Science Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/practical-data-science-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781783980246)

* [Python Geospatial Development - Second Edition](https://www.packtpub.com/application-development/python-geospatial-development-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781782161523)
###Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
