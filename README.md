wep_app_performance_talk
========================

iRuby notebook on web application performance optimization

View as HTML here:

http://nbviewer.ipython.org/github/andrewsg/wep_app_performance_talk/blob/master/Performance%20presentation.ipynb

Some loose notes:

optimization steps:

- write the program. don't optimize before you actually run into problems. you can keep the information in this lecture in mind when you do your first pass, but don't sweat it too much.
- analyze before optimizing!
- reduce number of database queries and API calls
- optimize slow queries or calls
- hand off invariably time-consuming processes to background workers
- increase parallelism or speed up your code, maybe
- increase database or other resources, maybe
- cache, judiciously, and watch out for cache invalidation problems
