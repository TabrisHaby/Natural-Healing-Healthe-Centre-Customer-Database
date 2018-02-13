# Natural Healing Healthe Centre Customer Database

  # Version 1 : 2017-02-08

  # Version 2 : 2018-01-16

      # Add new table Duration : record each treatment durtion for different customers

      # delete table estimated_income : estimate value based on internet data is not accurate

      # connect Insurance Table to consumption_habit table directly

      # correct Sunlife company contact number in Insurance table

  # Working Environment

    # OS : Windows 10 v1702 64 bit + Ubuntu 16.04.3 LTS

    # SQL : MySQL 5.7.20

    # SQL GUI : MysQL WorkBench 6.3

    # Analysis Software : Python 3.6.3

    # Analysis Software GUI : Spyder from Anaconda 5.0.1


# Database Details

  # About data

      # Data from two ways :

          # Client health history and conscent form

          # Paper and Online Questionares

      # data volumes :

          # Around 5000 rows and 18 variables in total


  # There are 11 tables in total, which are :

        # Customer : Customer general information, like name,gender,gender,phone,email,etc

        # Address : Address location information, like city, province, post code, etc

        # Address Area : Divide the area into different geographical districts

        # Customer Service Duration : connection of Service, Duration and Customer table. This is a mant-to-many connection

        # Service : Service treatment Information.

        # Duration : Duration for each treatment

        # Consumption Habit : many-to-many connection of Customer table and Treatment Frequency, Insurance table,Payment Method table,How_to_know table

        # Treatment Frequency : Treatment Frequency for each customers, customers Consumption Habit

        # Insurance : Insurance company for each customer, customers Consumption Habit

        # Payment Method : Payment method each customer prefer, customers Consumption Habit

        # How_to_know : from questionare, check the methods that customers know us, find the best way for advertising
