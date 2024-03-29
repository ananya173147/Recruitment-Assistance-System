# Recruitment Assistance System (RAS)

RAS is aimed towards making the recruitment process easy for the recruiters/hiring managers.
The recruiters can upload data, specify criteria, apply some filters, and shortlist applicants.
The system also provides a user-friendly GUI to the user to make the work easier.

![image](https://user-images.githubusercontent.com/59045952/119938937-c24b6a80-bfaa-11eb-8e2b-93fb0436e267.png)

![image](https://user-images.githubusercontent.com/59045952/119939237-2a9a4c00-bfab-11eb-9499-bf74ba107fe8.png)

### Frequently asked questions (FAQ)

#### How to use?
                  
* Upload in the correct format (.csv) at home page
* Apply the filters
* Export to download both shortlisted and rejected entries
               
#### What type of files can I upload?
 Comma Separated Values (.csv)
 
#### What is good data? 
Data which allows you to make an Excel Table directly, without any manual clean up is called good data. It should ideally be like a table. Additionally,
* Each column must have a heading
* No blank headings
* No duplicate headings
* No formulas in headings                        
* No merged cells
* Only one meaning in each column
* Same data type in a column.
* Blank cells where data is not available are ok.
* No rows or columns which are entirely empty
* Lower the number of different names of the same category, cleaner are the criteria selection options provided.
                    


### Initializing

```
npm run init
```


### Running

Testing:
```
npm test
```

Running:
```
npm start
```
