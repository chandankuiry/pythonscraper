from bs4 import BeautifulSoup
import requests
url =raw_input("enter Url for processing ")
r=requests.get("http://" + url)
data =r.text
soup =BeautifulSoup(data,'html5lib')
#for finding all of url
for d in soup.find_all("a"):
	print d.get('href')
#for finding the title of the site
print "title' ,soup.title

