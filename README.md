# Note-Taking-App
• This is a simple no-frills note taking app with material design, meant for taking down a quick note or list.

• Notes are saved automatically so you never have to worry about losing anything.

• 𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐲 𝐔𝐬𝐞𝐝 :
1. 𝐃𝐀𝐎'𝐬 : Accessing data using Room DAOs which manages local data SQLite data source using objects.

2. 𝐑𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐲 : clean API for UI to communicate with.

3. 𝐕𝐢𝐞𝐰𝐌𝐨𝐝𝐞𝐥 : Holds all the data needed for the UI.

• Load LiveData from ViewModel into RecyclerView.

First Case : Here, User allowed to enter the quick note. 

 ![Screenshot (454)](https://user-images.githubusercontent.com/79192605/119723181-cbddb100-be8a-11eb-9b26-57a1d27a4102.png)
 
 Second Case : Suppose, We have entered "Elon Musk and press on to the submit button", a POP-UP notification is shown with "Elon Musk Inserted". 
 
![Screenshot (455)](https://user-images.githubusercontent.com/79192605/119723215-d6984600-be8a-11eb-87e5-cca3a83cac0b.png)

Third Case : Here, We have entered the second data which is "Mukesh Ambani" and press on to the submit button, a POP-UP notification is shown with "Mukesh Ambani Inserted". 

![Screenshot (456)](https://user-images.githubusercontent.com/79192605/119723230-d9933680-be8a-11eb-84e7-24d936f5c916.png)

Fourth Case : Here, we have deleted "Mukesh Ambani" with the help of delete button, which is in the corner of the each notes. And a POP-UP notification is shown with "Mukesh Ambani Deleted". 

![Screenshot (457)](https://user-images.githubusercontent.com/79192605/119723235-dbf59080-be8a-11eb-9a1a-88ae857ef184.png)

Fivth Case : Here, We have checked, whether the notes, that we have created is stored into the app after killing that application. 

![Screenshot (458)](https://user-images.githubusercontent.com/79192605/119723247-de57ea80-be8a-11eb-8914-23906138b8a0.png)
