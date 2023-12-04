<div>
<h1>
<center>
Coffee-Search
</center>
<h1>



<p>
<center>
    <img src="Pictures/logo_v1.png">
</center>
<p>


## Overview

This exploratory project is meant to use Yelp data to help users determine what the best coffee shop is under their given criteria. The purpose is to create an end-to-end pipeline, sourcing the data, configuring it appropriately, and creating an accessible UI for anyone to use this tool.

## Tasks

**Sourcing the data**
- create a reliable connection to Yelp API
- figure out search extent needed for the project (geographically)

**Data Engineering**
- reliable back-end code for ETL
- use Python

**Data Presentation**
- creating relevant charts, search bars, criteria inputs for users to manipulate the data
- use Python/Django

**UI/UX**
- build a front-end that references the prior steps in a smooth process
- use React/JS

**Misc Admin**
- figure out how to structure a repo best practice for this type of web application

## Virtual Environments

Since this is a learning exercise, I am including notes on working in a virtual environment. Below are the steps to create it using the command prompt.

```
$ python -m pip install --user -U virtualenv 
```
Once installed, you can do the following once in the desired folder:
```
$ virtualenv env
```
OR
```
$ python -m virtualenv env
```
To activate the new virtual enviornment:
```
$ source env/bin/activate # on Linux or Mac
$ env\Scripts\activate    # on Windows
```
In this repo, since there is a `requirements.txt` file, you can call it in your virtual environment by submitting this line of code in the virtual environment:
```
$ pip install -r requirements.txt
```