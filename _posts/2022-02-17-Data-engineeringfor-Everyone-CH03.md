---
layout: post
title: Data Engineering for Everyone
subtitle: Chapter 03
categories: Website
tags: [Github, Website]
---

## Data Processing value
1. Remove unwanted data
2. To save memory
3. Convert data from one type to another
4. Organize data
5. To fit into a schema/structure
6. Increase productivity

## How Data Engineers Process Data
1. Data manipulation, and tidying tasks:
* that can be automated
* that will always need to be done
2. Store data in a sanely structures database
3. create views on top of the database tables
4. rejecting corrupt song files
5. deciding what happens with missing metadata
6. create views on top of the database tables
7. seperates artists and albums tables.. 
8. optimizing the performance of the database
9. indexing 

## Scheduling Data 
1. Can apply to any task listed in data processing
2. Scheduling is the glue of your system
3. Holds each piece and organize how they work together

## Mnaul, time, and sensor scheduling
1. Manually    
manually pdate the employee table at 6am    

2. Automatically/time     
Automatically update the table every 6am 

3. Automatically/ conidtion   
Automatically update the table if a new emplyee is added

* Sensor scheduling

## Batches and Streams
1. Batches 
* Group records at intervals
* Often cheaper
2. Streams
* send individual records right away

## Parallel computing
1. Basis of modern data processing tools 
2. Necessary 
* Mainly because of memory 
* also for processing power
3. How it works:
* Split tasks up into smaller subtasks 
* Distribute these subtasks over several computers

# benefits and risks of parallel computing
1. employees = processing units
2. advanatges 
    * extra processing power 
    * reduced memory footprint
3. disadvantages
    * moving data incurs a cost 
    * communication time

## Cloud Computing

# Servers on permises 
 1. Bought
 2. need space
 3. electrical and maintenance cost
 4. enough power for peak moments
 5. processing power unused at quieter times

 # Servers on the cloud
 1. rented
 2. don't need space
 3. use just the resources we need
 4. when we need them
 5. the closer to the user the better

 ## cloud computing for data storage
 1. database reliability: data replication
 2. risk with sensistive data
 

## Multicould

* Pros:
    * Reducting reliance on a single vendor 
    * Cost-efficiencies
    * Local laws requiring data to b physcially present within the country
    * Militating against disasters
* Cons:
    * Cloud providers try to lock in consumers
    * Incompatibility 