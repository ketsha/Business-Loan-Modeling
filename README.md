# Business Loan Modeling
# Business Objective
  The objective of the Business Loan Modeling project is to predict how much loan will be approved by the SBA & their registered lenders when a business applies for a loan through the SBA. 
  
  The Small Business Administration (SBA) was founded in 1953 to assist small businesses in obtaining loans. Small businesses have been the primary source of employment in the       United States. Helping small businesses help with job creation, which reduces unemployment. Small business growth also promotes economic growth. One of the ways the SBA helps     small businesses is by guaranteeing bank loans. This guarantee reduces the risk to banks and encourages them to lend to small businesses. If the loan defaults, the SBA covers     the amount guaranteed, and the bank suffers a loss for the remaining balance.

![name-of-you-image](https://github.com/ketsha/Business-Loan-Modeling/blob/main/SBA%20Loan%20High%20Level.png?raw=true)

  The SBA works with lenders to provide loans to small businesses. The agency doesn’t lend money directly to small business owners. Instead, it sets guidelines for loans made by     its partnering lenders, community development organizations, and micro-lending institutions. The SBA reduces risk for lenders and makes it easier for them to access capital.       That makes it easier for small businesses to get loans.
  
  Loans guaranteed by the SBA range from small to large and can be used for most business purposes, including long-term fixed assets and operating capital. Some loan programs set   restrictions on how you can use the funds, so check with an SBA-approved lender when requesting a loan. Your lender can match you with the right loan for your business needs.

# What you need to know about SBA Loan
![name-of-you-image](https://github.com/ketsha/Business-Loan-Modeling/blob/main/What%20you%20need%20to%20know%20about%20Loan.png?raw=true)
# Business Loan Eligibility requirements
  Lenders and loan programs have unique eligibility requirements. In general, eligibility is based on what a business does to receive its income, the character of its ownership,     and where the business operates. Normally, businesses must meet size standards, be able to repay, and have a sound business purpose. Even those with bad credit may qualify for     startup funding. The lender will provide you with a full list of eligibility requirements for your loan.

    Following are the baseline eligibility requirements:
    # Be a for-profit business
      The business is officially registered and operates legally.
    # Do business in the U.S.
      The business is physically located and operates in the U.S. or its territories.
    # Have invested equity
      The business owner has invested their own time or money into the business.
    # Exhaust financing options
      The business cannot get funds from any other financial lender.

![name-of-you-image](https://github.com/ketsha/Business-Loan-Modeling/blob/main/business-loan-factors-1.jpg?raw=true)
# Business Loans for exporters
  Most U.S. banks view loans for exporters as risky. This can make it harder for you to get loans for things like day-to-day operations, advance orders with suppliers, and debt     refinancing. That’s why the SBA created programs to make it easier for U.S. small businesses to get export loans.

# The Business Loan Data Set (Reference : www.kaggle.com)
  The original data set is from the U.S.SBA loan database, which includes historical data from 1987 through 2014 (899,164 observations) with 27 variables. The data set includes   information on whether the loan was paid off in full or if the SMA had to charge off any amount and how much that amount was. The data set used is a subset of the original       set. It contains loans about the Real Estate and Rental and Leasing industry in California. This file has 2,102 observations and 35 variables. The column Default is an integer   of 1 or zero, and I had to change this column to a factor.
  
            Variable Name			Description
            LoanNr_ChkDgt			    Identifier Primary key
            Name	        		    Borrower name
            City	        		    Borrower city
            State	        		    Borrower state
            Zip	        		      Borrower zip code
            Bank	        		    Bank name
            BankState			        Bank state
            NAICS	        		    North American industry classification system code
            ApprovalDate			    Date SBA commitment issued
            ApprovalFY			      Fiscal year of commitment
            Term	        		    Loan term in months
            NoEmp	        		    Number of business employees
            NewExist			        1 = Existing business, 2 = New business
            CreateJob			        Number of jobs created
            RetainedJob			      Number of jobs retained
            FranchiseCode			    Franchise code, (00000 or 00001) = No franchise
            UrbanRural			      1 = Urban, 2 = rural, 0 = undefined
            RevLineCr			        Revolving line of credit: Y = Yes, N = No
            LowDoc Loan Program 	Y = Yes, N = No
            ChgOffDate			      The date when a loan is declared to be in default
            DisbursementDate		  Disbursement date
            DisbursementGross		  Amount disbursed
            BalanceGross			    Gross amount outstanding
            MIS_Status			      Loan status charged off = CHGOFF, Paid in full =PIF
            ChgOffPrinGr			    Charged-off amount
            GrAppv				        Gross amount of loan approved by bank
            SBA_Appv			        SBA’s guaranteed amount of approved loan

# Technical Stack
  The Business Loan Modeling project will use Azure Synapse, Azure Machine Learning, Azure DataLake Gen 2 and PowerBI.
  
# Architecture Overview
![name-of-you-image](https://github.com/ketsha/Business-Loan-Modeling/blob/main/HighLevelReferenceArchitecture.JPG?raw=true)
<img src="https://github.com/ketsha/Business-Loan-Modeling/blob/main/HighLevelReferenceArchitecture.JPG" width="300" />
