# Automatic LinkedIn Skills Endorser
I built this notebook so that you don't have to spend your precious time to endorse people's skills.

## Project Intro/Objective
At the end of Metis Data Science Bootcamp, we wanted to endorse each other's skills. However, there were too many to go through. Therefore, I wrote a simple notebook that lets you enter your desired people's LinkedIn profile urls, and Selenium driver will go to each one's profile and endorse all skills

## Notable Technologies Used
* Python 3, Jupyter Notebook
* Selenium, 
* OpenCV

LinkedIn's tag values are dynamic, so can't use conventional techniques(BeautifulSoup and Selenium) to achieve this.
OpenCV(image detection) was used with simple scripting to replicate what you can do with BeautifulSoup or Selenium.

## Working Demo
I put long wait times to weave around bot detection mechanism, but havn't played long enough with it to find the optimal time.
Wait time can be shortened to quicken the process, but the intent of this script is so that you can just have it run while you are off doing something else so you don't have to spend your precious time.  
https://www.youtube.com/watch?v=vk9k0AZ2eGc&feature=youtu.be
