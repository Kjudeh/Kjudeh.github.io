---
layout: post
title: Python Notes dictionaries
subtitle: to be updated periodically
categories: Website
tags: [Github, Website]
---

# Definition of countries and capital
countries = ['spain', 'france', 'germany', 'norway']
capitals = ['madrid', 'paris', 'berlin', 'oslo']

# Get index of 'germany': ind_ger
ind_ger = countries.index ('germany')


# Use ind_ger to print out capital of Germany
print(capitals [ind_ger])   

dictionaries use {}  
keys() shows the dictionary keys  

to find a key value right print('' in dictionary)  
i.e. italy in europe  
you can delete entire by using del()  
changing entries values by using [] (like lists)  


# Dictionary of dictionaries
europe = { 'spain': { 'capital':'madrid', 'population':46.77 },
           'france': { 'capital':'paris', 'population':66.03 },
           'germany': { 'capital':'berlin', 'population':80.62 },
           'norway': { 'capital':'oslo', 'population':5.084 } }


# Print out the capital of France
print(europe['france']['capital'])

# Create sub-dictionary data
data = {'capital':'rome','population':59.83}

# Add data to europe under key 'italy'
europe['italy'] = data

# Print europe
print(europe)