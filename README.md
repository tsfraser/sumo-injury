# sumoinjury

A small project to probe the effect of injuries in professional level sumo wrestling, and how it affects when a wrestler (Rikishi) retires. This project is split into major components:

SumoScraper: A webscraper that scrapes SumoDB to extract wrestler info, focusing at wrestler that rank at Juryo level or above at least once in their career. [Nearly complete]
SumoInjury: A small neural net that, given parameters of a wreslter (length of career, age, win/loss/withdrawals over recent matches) determines the following: the probability of their next injury being career ending. Currently under work.

General use comments:
  If anyone wishes to use the webscraper, please be very careful. SumoDB is a small website, so scrape with caution, do your best to not knock it out. It is an invaluable resource, and I would not want any code I've written to be responsible for any inconvenience. It is for this reason that if you want the data, you can just access it from the repo.
  
The current project focuses on the upper echelons of sumo (Juryo rank and above), where wrestlers compete in 15 matches over 15 days. I plan to expand my scraper to include lower ranks (including the lowest salaried ranks) soon, but for now, I just want to get the basic infrastructure in place.

I will update this more when the project becomes useable. Currently committing here for posterity.
