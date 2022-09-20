# 0x16. API advanced
____________________________________________________
![image](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/314/WIxXad8.png)  
____________________________________________________
## Learning Objectives

### General  
- How to read API documentation to find the endpoints you’re looking for  
- How to use an API with pagination  
- How to parse JSON results from an API  
- How to make a recursive API call  
- How to sort a dictionary by value  
_____________________________________________________
## Tasks

**0. How many subs?**
- Write a function that queries the Reddit API and returns the number of subscribers (not active users, total subscribers) for a given subreddit. If an invalid subreddit is given, the function should return 0.

Hint: No authentication is necessary for most features of the Reddit API. If you’re getting errors related to Too Many Requests, ensure you’re setting a custom User-Agent.

____________________________________________________
**1. Top Ten**
- Write a function that queries the Reddit API and prints the titles of the first 10 hot posts listed for a given subreddit.
____________________________________________________
**2. Recurse it!**
- Write a recursive function that queries the Reddit API and returns a list containing the titles of all hot articles for a given  
subreddit. If no results arefound for the given subreddit, the function should return None.
____________________________________________________  
