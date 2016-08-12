# Introduction

This program will Analysis sar log file, generate all information like {'table':{name:{field:[values,]}}, 'date',}

The sar.json is a json file format {'field key word': 'table name'} to mark the unique field and table.

## The idea

Every item in sar log can regard a table and every table has a unique field, so a unique field is a mark of table. Store this information to file sar.json.

You maybe need edit, add or remove key-value pair in sar.json makesure the table you need can be get.

## How to use

The sar_parser.py has a function  parser to return a dict with all information in sar log file.Before call it, run```./sar_parser.py [log file] sar.json```for a test, you can also edit test function in sar_paser.py to print what you want.
