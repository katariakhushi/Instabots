# Instabots
## Overview
This repository contains a set of Python scripts that automate various tasks on Instagram using Selenium and BeautifulSoup. The bot performs tasks such as logging in, searching profiles, following/unfollowing users, liking/unliking posts, extracting followers, and checking stories. This README provides instructions for setting up and using the bot.

## Prerequisites
* Python: Ensure you have Python 3.6 or later installed.
* Selenium: Install the Selenium library using pip install selenium.
* BeautifulSoup: Install BeautifulSoup using pip install beautifulsoup4.
* ChromeDriver: Download and place chromedriver executable in a location accessible to your script.
## Setup
* Install the required packages:

Install Selenium and BeautifulSoup using pip.
* Download ChromeDriver:

Download the ChromeDriver executable from the official site and update the path in the script.
* Configuration
Update the username and password variables in the script with your Instagram credentials.

## Functions
* 1. Log In
Logs into your Instagram account.

* 2. Search
Searches for a term and prints the names of Instagram handles (excluding hashtags).

* 3. Open Profile
Searches for and opens a profile by username.

* 4. Follow/Unfollow
** Follow a user: Follow users if not already following.
** Unfollow a user: Unfollow users if currently following.
* 5. Like/Unlike Posts
Like the top 30 posts of a profile: Likes posts if not already liked.
Unlike the top 30 posts of a profile: Unlikes posts if currently liked.
* 6. Extract Followers
** Extract usernames of the first 500 followers from a profile.
** Print all followers of a profile that you follow but who don’t follow you.
* 7. Check Story
Checks if the story of a user has been viewed or not.
