visual_news_interface
=====================

Final Project for the Visual Interfaces for Computer class @ Columbia University

We implemented a visual interface that solves a journalistic problem - assisting audiences with disabilities to better access news articles. These people might have difficulty searching, filtering, and reading news on the web; audible news would be greatly helpful to them. Users can apply gestures to manipulate the system and search for breaking national news and breaking international news via the Google News Search engine.

List of files according to dependence:

visual_news_interface.py
	constants.py
	skin.py
	imgproc.py
	gesture.py
	news.py


The visual_news_interface.py is our main function of this project. It imports constants.py, skin.py, imgproc.py and gesture.py applications to initialize and analyze hand gestures. The main program also imports the news.py application to search and filter news articles from the mainstream media press.

System and Tool Configurations
 
OS: Mac OSX
Library: Python 2.7, JPEG, Python Imaging Library, OpenCV, BeautifulSoup
		Installation Process
          		$ curl -O -L http://effbot.org/downloads/Imaging-1.1.7.tar.gz
				$ tar -xzf Imaging-1.1.7.tar.gz cd Imaging-1.1.7
				$ python setup.py build
				$ sudo python setup.py install
				An alternative installing approach using pip:
				$ sudo pip install PIL
			
			OpenCV for Python
				Installation Process
				##Install numpy with Macports
				$ sudo port install py27-numpy

				##Install OpenCV with Python
				$ sudo port install opencv +python27
				 
				##Edit your ~/.bash_profile with:
				$ open -t ~/.bash_profile
				 
				##Add the line:
				export PYTHONPATH=/opt/local/var/macports/software/opencv/2.2.0_0+python27/opt/local/Library/Frameworks/Python.framework/Versions/2.7/lib/python2.7/site-packages:$PYTHONPATH
			BeautifulSoup
				#Installation Process
				easy_install BeautifulSoup
			Requests
				#Installation Process
				easy_install requests

