### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### NAME : ANISHA V
### REG NO. : 212224040023
### DATE: 25-07-26

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
<img width="1235" height="832" alt="image" src="https://github.com/user-attachments/assets/ad2cbb38-6a16-4121-9390-81ec1fd1dfa2" />
<br>
<img width="1255" height="922" alt="image" src="https://github.com/user-attachments/assets/952fa5b5-b78a-4b77-a383-efb91b22d2e9" />

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
#### emp:
<img width="1248" height="931" alt="image" src="https://github.com/user-attachments/assets/fdf34ee7-cc6c-4acd-a63a-721a48a5f61e" />
<img width="1788" height="940" alt="image" src="https://github.com/user-attachments/assets/945abe5f-a424-44a9-8d2c-47e9897e2be2" />
#### weather:
<img width="1245" height="936" alt="image" src="https://github.com/user-attachments/assets/81d57cfa-83bd-4424-b06c-27142b9f99a2" />
<img width="1257" height="940" alt="image" src="https://github.com/user-attachments/assets/21073080-9a20-4c38-9dfc-9fc36fed458e" />

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
#### emp:
<img width="1787" height="942" alt="image" src="https://github.com/user-attachments/assets/6ca89aeb-93b3-4c6d-a5bb-fc476826b309" />
<img width="1771" height="925" alt="image" src="https://github.com/user-attachments/assets/987ccf8b-a830-442e-9ece-26460af606a4" />

#### weather:
<img width="1251" height="940" alt="image" src="https://github.com/user-attachments/assets/f9ac39c1-59c5-48e4-9b8e-dbe3bffc9570" />
<img width="1248" height="946" alt="image" src="https://github.com/user-attachments/assets/96a029dd-4cdf-4968-ad4f-084489765c61" />

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
#### emp:
<img width="1647" height="942" alt="image" src="https://github.com/user-attachments/assets/64183471-b927-4346-adbf-4237d0c95f77" />

#### weather:
<img width="1245" height="935" alt="image" src="https://github.com/user-attachments/assets/c39352b3-c9bd-4f25-9062-b3bb483032ec" />

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
