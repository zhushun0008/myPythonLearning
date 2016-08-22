my Python Learning
================

Academic Training from Enthought for speeding up learning Python

### 1. Trick 
1. Sample data
  * Refer to [Shuffle data](http://stackoverflow.com/questions/11765061/better-way-to-shuffle-two-related-lists)
  * Use shuffle to get index
  * for loop to separate training data set and test data set
2. Move Copy files to destination 
  *  os package
  *  [shutil package](https://docs.python.org/2/library/shutil.html)
      * shutil.copy()  

## Python Usage

* [PEP 0008 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
* [Code Like a Pythonista: Idiomatic Python](http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html)
* [PEP318 Decorators for Functions and Methods](https://www.python.org/dev/peps/pep-0318/)
* [PEP 0333 -- Python Web Server Gateway Interface v1.0](https://www.python.org/dev/peps/pep-0333/)
* [Python regular expression documentation](https://docs.python.org/2/library/re.html)
* [How To Use Linux epoll with Python](http://scotdoyle.com/python-epoll-howto.html)
* 
### Decorators

* [Python装饰器学习](http://blog.csdn.net/thy38/article/details/4471421)
* [原来Python装饰器就是这么个东西](http://pythonmap.iteye.com/blog/1682696)
* [PEP 0318 -- Decorators for Functions and Methods](https://www.python.org/dev/peps/pep-0318/)

### commands
1. commands.getstatusoutput(cmd)

Execute ***cmd*** command and return the tuple of (status, output_of_cmd)

 ```
 commands.getstatusoutput('ls /bin/ls')
 # (0, '/bin/ls')
 commands.getstatusoutput('cat /bin/junk')
 # (256, 'cat: /bin/junk: No such file or directory')
 ```

## Module 
### Tornado
