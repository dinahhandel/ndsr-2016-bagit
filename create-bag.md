# CREATE A BAG

Instructions for creating a BagIt bag with the Python build.

## BEFORE YOU BEGIN

- You installed the Python BagIt module.
- You downloaded the zip package of samples and resources. Save **A COPY** of the _NDSR_BagIt_samples_01_ folder on your Desktop. (Leave the downloaded zipped version in your Downloads folder.)

## CREATING BAGS WITH BAGIT ON THE COMMAND LINE

1. Open Terminal (Applications > Utilities > Terminal)
2. In Terminal, type the command below. You will see usage and options information for BagIt. Read through them.

       `bagit.py --help`


3. What does 'creating a bag' actually mean? You will create a structured package of target data based on an existing structure. On the desktop, open _NDSR_BagIt_samples_01_ and review the files inside to understand your source data.
    - What types of files are in the folder?
    - What information is in the text files?
    - How many files are in the folder?
    - Want to see how your data looks on the command line instead of opening the files in Finder? Enter these commands into Terminal:
        - `cd [drag and drop the _NDSR_BagIt_samples_01_ folder into Terminal]` _Changes the directory to our samples_
        - `ls` _Lists the files within our sample directory_
        - `cat [drag and drop one of the text files]` _Prints/displays the contents of a text file into Terminal_

4. It's time to create the bag, or package your data into a bag _payload_. In Terminal, enter the command below. **IMPORTANT: This will REPLACE the folder on your Desktop with a BagIt-structured bag.** This action is referred to as "bag in place", or replacing a data source with a bag that adheres to the BagIt specifciation.  

        - `bagit.py --contact-name '[FirstName LastName]' [directory of sample files]`

5. Congratulations! You made a bag! :tada:

## WHAT'S IN YOUR :pouch:?

1. Time to open up the bag and see what's inside. You can use the commands you tried in Step 3, or simply double click the text files from the Finder window. What you should see:
![bag_01 structure](https://github.com/kgrons/ndsr-2016-bagit/blob/master/bag_01_structure.png "Bag_01 Structure")


