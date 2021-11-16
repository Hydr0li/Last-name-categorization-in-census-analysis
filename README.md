# Last name categorization in census analysis
By using Python to Categorized and verified last names of Indian indigenous people from the 1900 US census according to the names’ language family origin.

Designed and wrote the algorithm that involves about 833,000,000 calculations and comparison to conduct the categorization and verification the last name belongs to which nationality, with the help of Python, JupyterNotebook.

---

## Description
Categorizing names from the 1900 census and verifying them in original census data has a huge size of data base and all the names should be categorized to over 90 orinial countries such as Chen is a Chinese_English name and other names might belong to Croatian_English_German_Hungarian_Lithuanian_Serbian_Swedish name or Arabic_English name.

At the very beginning, the 1900 census data has lots of empty and invalid data, so cleaning the data set is the first task, also, you don't want to delet the non-english words because that might be the someone's name. Also, we need to delet the invalid data, for the missing names, delete the row and for the unimportant data missing, we just ignore it and directly remove the whole column, as for the defination of the "unimportant data", the census contains the location of the names or where this person comes from, the only task we are going to do is comparing census names and original names, so, we can just delete the "unimportant data" sets.

Then we need to integrate some name origins such as Arabic_English and Arabic_English_Afganastan name will be integrated as Arabic names since the Arabic comes first which means it is mainly comes from Arabic language. 

Then, comparing, since it is a 833,000,000 huge number of comparisons, I did the coding on my computer and run it on cloud computer in Virginia Tech.
