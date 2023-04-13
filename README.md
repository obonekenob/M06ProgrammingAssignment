# M06ProgrammingAssignment  
  
  Assignment done in Jupyter notebook except for Ecercise 15.1.  
  Please run multi_times.py for Exercise 15.1  
    
  =======================  
  
   ---  
   I got this error using the book soution.
   Changed to stmnt to time.strptime(today_string, fmt) and it workrd.  
  
  """ SDEV220  
    Paul R Thompson  
    Chapter 13 Exercise 3 (13.3)  
"""  
fmt = '%Y-%m-%d\n'  
datetime.strptime(today_string, fmt)  
------------------------------------------  
AttributeError                            Traceback (most recent call last)  
~\AppData\Local\Temp\ipykernel_16368\1318585474.py in <module>  
      4 """  
      5 fmt = '%Y-%m-%d\n'  
----> 6 datetime.strptime(today_string, fmt)  
  
AttributeError: module 'datetime' has no attribute 'strptime'  


