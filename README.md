# Python and Lambda Project

In this project, i wrote a python script to solve a real world problem for a company that wanted me to provide a solution to the challenge below:

Question:

A Client drops many files into an S3 bucket we own.
We want to organize the files by day.
Write a lambda script to trigger when a file lands in an S3 bucket, and move it to a folder named YYYYMMDD/filename based on when the file was created in the S3 bucket.


So basiscally, this company has an S3 bucket in which a client puts his/her files. The lamda script we will write will create a folder in the S3 bucket that is named year, month and day(YYYYMMDD) and the script will organize the files the customer is putting into the S3 bucket into the folder based on the day the customer put the files in the S3 bucket.
