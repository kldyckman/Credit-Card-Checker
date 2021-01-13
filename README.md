# Credit-Card-Checker
Optimizes credit card verification process using knowledge of functions and loops to handle multiple credit cards at a time.

There are 15 arrays that each contain the digits of separate credit card numbers. They all have prefixes to reflect their status, i.e. variables that start with valid contain a valid number, whereas invalid do not, and mystery variables can be either. There is also a batch array that stores all of the provided credit cards in a single array.

The purpose of validateCred() is to return true when an array contains digits of a valid credit card number and false when it is invalid, using the Luhn algorithm.

The role of findInvalidCards() is to check through the nested array for which numbers are invalid, and return another nested array of invalid cards.

The function idCardCompany() returns the credit card company for a particular credit card number.

The function idInvalidCardCompanies() returns an array of companies that have mailed out cards with invalid numbers, not including duplicates.
