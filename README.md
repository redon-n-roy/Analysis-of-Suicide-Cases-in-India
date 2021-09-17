# Analyzing the suicide cases in India

## Project Description

The aim of our project was to analyze the data of suicide cases in India during the period 2001-2012 to findout suicide rates and different reasons due to which people have committed suicide in India. It is very important to understand the reasons to commit suicide and Data Science helps in this regard. Here we analyzed the data by taking various parameters available within the dataset.


## Technologies Used

* Python 2.7
* PySpark 2.3.2
* Spark 2.3.2
* SparkSQL 2.3.2
* Hive 2.1.0
* Hadoop 2.7.3
* Git/GitHub  

## Features

List of features ready and TODOs for future development

* What is the percentage of change in suicide cases?
* Which is the age group having the most suicide cases?
* What is the professional profile of the people who committed suicides?
* Which state had the most suicide cases?
* What are the treads in various causes of suicide?

## Dataset Definition

* state - Shows the name of the state where suicide happened.
* year - Shows the year in which the suicide happened.
* type_code - Shows the general category of the suicide.
* type - Show the specific category of suicide within the general category.
* gender - Shows the gender of the suicide victim.
* age_group - Shows the age group in with the suicide victim belongs to.
* case_count - Show the total cases in that particular category.

## Getting Started

> All the operations below are for Windows OS
   
* Make sure that the virtualization is enabled for your system from the BIOS.
* Install VMware Workshation Player.
* Download and install Hortonworks HDP 2.6.5.
* Get everything up and runninng.
* Connect to the system either through the webshell/OpenSSH/PuTTY.
* Upload all the required files into the local system or clone this repo.

```
git clone https://github.com/redon-n-roy/Analysis-of-Suicide-Cases-in-India.git
```


> For linux, install all the dependencies and then run the project from the command-line.

## Usage

To run the hive queries, use the Hive shell

Once the data is loaded into hive, use the `spark-submit` command to run the python program in this repo or use `pyspark` to run each command/operations manually.

# Contributors

* [Meenal Shree](https://github.com/meenal-shree)
* Neha Kumari
* Nirosha M

# License

 This project uses the [MIT](./LICENSE) license.

# References
 [Dataset](https://www.kaggle.com/rajanand/suicides-in-india)
