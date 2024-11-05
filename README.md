### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 

### AIM: 

  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
  
### PROCEDURE: 

1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:

# EMPLOYEE DATA
![Screenshot 2024-11-05 215751](https://github.com/user-attachments/assets/21aaf8b2-716d-4138-8497-0c932e0f4b0f)


# WEATHER DATA
![Screenshot 2024-11-05 215759](https://github.com/user-attachments/assets/a2fd2c13-0f88-4185-993c-df016117a914)


### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

# EMPLOYEE DATA
![Screenshot 2024-11-05 215815](https://github.com/user-attachments/assets/fce2cab3-4d23-42a6-90e4-59826fd56c48)

# WEATHER DATA

![Screenshot 2024-11-05 215825](https://github.com/user-attachments/assets/9b95f0a8-1c7e-4f19-ad69-9cdd77d587d5)

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

# EMPLOYEE DATA
![Screenshot 2024-11-05 215833](https://github.com/user-attachments/assets/cdb5c336-a1ec-478f-94e8-730773f0772c)


# WEATHER DATA
![Screenshot 2024-11-05 215839](https://github.com/user-attachments/assets/810591fa-415b-439d-898d-19ad40c50dfe)


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:

# EMPLOYEE DATA
![Screenshot 2024-11-05 215848](https://github.com/user-attachments/assets/ea92105a-b0ab-4719-b7db-a8d6a5255b65)


# WEATHER DATA
![Screenshot 2024-11-05 215855](https://github.com/user-attachments/assets/991e55da-83b6-4199-a224-ecedcabc5b7e)

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
