# python_server-static_PNG_map

https://www.sparkfun.com/tutorials/403
````
  -download pyserial
  -download numpy (use: http://www.lfd.uci.edu/~gohlke/pythonlibs/)LINUX- http://math.berkeley.edu/~shaowei/python.html
  -download mathplotlib
  (you must download the version for your os 64 or 32)
  
  python setup.py install
  
  -edit global vars in pn.
  name: python
  command: python
  folder: %d
  parameters: -i %f (use -i so that the window doesn't close, then you can see debug info)
  
  
  *unexpected indent error: you need 4 space tabs, don't use spaces, only tabs. Highlight a block and tab it to get spaces out.
````

Also, the maps don't refresh automatically, so as your GPS logs data, you will need to close the map window and run the map generation commands to get new data. If you close the entire Python program, the logging to nmea.txt halts. 