---
layout: post
title: Data Engineering for Everyone
subtitle: Chapter 02 
categories: Website
tags: [Github, Website]
---

## Structured Data

1. Easy to search and organize
2. consistent model, rows and columns
3. Defined types
4. Can be grouped to form relations
5. Stored in relational databases
6. About 20% of the data is structured 
7. Created and queried using SQL

## Semi-Structured Data

1. Relativley easy to search and organize
2. COnsistent model, less-rigid implementation: different observations have different sizes
3. Different types. 
4. Can be grouped, but needs more work
5. NoSQL databases: JSON, XML, YAML 

## Unstructured Data
1. Doesn't follow a model, can't be contained in rows and columns
2. Difficult to search and organize
3. Usually text, sound, pictures, or videos
4. Usually stores in data lakes, can appear in data warehouses or databases
5. Most of the data is unstructured 
6. Can be very valuable

# We can add structure
1. Use AI to search and organize unstructred data
2. Add information to make it smei-structured 


## SQL Databases
1. Structured Query Language
2. Industry standard for Relational Database Management System (RDBMS)
3. Allows you to access many records at once, and group, filter, or aggregate them
4. Close to written English, easy to write and understand
5. Data engineers use SQL to create and maintain databases
6. Data scientists use SQL to query (request information from) databases

## Data Warehouses and Data Lakes
Data Lake 
1. Stores all the raw data
2. Can be pertabytes
3. Store all data structures
4. Cost effective
5. Difficult to analyze
6. Requires an up-tp-date data catalog 
7. Big data, real-time analytics           
Data warehouse
1. Specific data for specific use
2. Relatively small
3. Stores mainly structured data
4. More costly to update
5. Optimized for data analysis 
6. Also used by data analysts and business analysts
7. ad-hoc, read-only queries

## Data catalog for Data Lakes 
1. What is the source of this data?
2. where is this data used?
3. who is the owner of the data?
4. How often is the data updates?
5. Good practice in terms of data governance 
6. No catalog ---> Data swamp

# Good practice for any data storage solution
1. Reliablity 
2. Autonomy
3. Scalability
4. Speed

A "database" is a very general term, and a data warehouse is a type of database. Data warehouses also have subsets, like data marts, which are highly curated for a particular community of users, such as a specific team Data marts are also much smaller, tens of gigabytes instead of the hundreds of gigabytes to petabytes of data that can be held in a data warehouse.

