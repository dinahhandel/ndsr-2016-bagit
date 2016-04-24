# MORE BAGIT ACTIVITIES AND SCRIPTS

Recommendations for activities and tasks to increase comfort with using the Python build of BagIt, including small scripts to accomplish tasks that were previously built into the CLI instance of the BagIt Java build.

## ADDING BAG METADATA WHILE CREATING BAGS
1. Use _NDSR_BagIt_sample_03_ to play around with bag metadata that can be added to the _bag-info.txt_ file. Read about the optional descriptive information you can include in that file in [Bag Metadata: bag-info.txt section of the BagIt spec](https://tools.ietf.org/html/draft-kunze-bagit-13#section-2.2.2). 

2. Add your phone number, a description, and a unique identifier when you create a new bag using the command line. 
- Options are structured like:
  `--optionName 'The information you want to add to the bag-info.txt file'
So a command would look like:
  `bagit.py --contact-name 'Kathryn Gronsbell' --contact-email 'kgronsbell at gmail dot com' --external-description 'There may be something a little off about this bag...' /Users/kathryngronsbell/Desktop/NDSR_BagIt_sample_02`

3. Look at the _bag-info.txt_ in the new _NDSR_BagIt_sample_03_. 
 - Does the bag metadata you entered in the command show up?
 - How could this be useful for an organization's collections? Having a dedicated field for external identifier and descriptive information increases transparency and interoperability. 

## "LIBRARY USAGE" aka PROGRAMMING TASKS RELATED TO YOUR BAGS

On the Library of Congress' [bagit-python page](https://github.com/LibraryOfCongress/bagit-python#library-usage), they include examples of Python scripts to accomplish certain tasks. 

cd to dir
 

