# msr_assignment2
 Note: This is a reproduction project as part of the MSR course 2022 at UniKo, CS department, SoftLang Team
• Names of team: Delta
• Students Name: 
        Abdullah Md Humayun Kabir
        Tanzina Mollah
        Mahbubul Alam Tuhin
     Objective of reproduction with subsections as follows:
     Description - For our claimed paper dataset was not available, so we took the part of data fetching from stackoverflow, we collected data from stackover flow dump.
     Input data - This is the claimed paper repository, https://github.com/Anonymousmsr/ASIM
     Output data (1+ lines) — provide links to the paper’s repo, if possible, and to your git project.

• Findings of reproduction with subsections as follows:
    Process delta:  The claimed paper had used the dataset of another publication where they had used questions of Java tags, and we had collected the data with Android tag.
     Output delta: As the claimed paper did not provide the used dataset and the stucture was also unclear the model was unable to run.

• Implementation of reproduction with subsections as follows:
    Hardware requirements : 
        1.6 GHz or faster processor
        1 GB of RAM
    Software requirements :
        libraries:
            tqdm
            nltk
            numpy
            scikit-learn
            msgpack-python
            tensorboardX
            json5
            xml.etree.ElementTree
        jupyter notebook
    •• Validation: In order to fetch the data at first extract the "data.zip" in data folder and run the "fetch.ipynb" file in extracted folder it will create a csv file with all the questions.
    •• Data: As we were unable to run the model we could only create a csv with all the question. Further more the related question id's are also fetched so we need to map them to the question bank and label them for further usage. 
