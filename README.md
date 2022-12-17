
# 1.Methodology

First a navbar is created and a homepage is implemented its  components,uses material ui that is stacks typography and boxes etc for the ui
And for routing purposes links and routes from react router dom are used
implemented search bar component on which on clicking the button and data is fetched from the api.
fetch api from react  fetches the data if we pass in the url and the options which are basically configurations that are needed.
The Fetch API through the fetch() method allows us to make an HTTP request to the backend. With this method, we can perform different types of operations using HTTP methods like the GET method to request data from an endpoint, POST to send data to an endpoint, and more.
It gives us a response then we can change it to json using response.json and use it
So options basically had headers which had our api details like host or key and a method which was get in my case
And to hide api key we can use env variables.
So where ever we want the data from the api we can call fetch data function
filter function returns the array of matching results for the searched name of target bodypart or equipment
To load the bodyparts data effect hook is used which will basically call a function whenever page reloads
 props are used to pass states across various component
flow-> app.js-> 2 pages->Home.js->exercisedetail.js
Hom.js has 3 components
Hero banner, search exercises and exercises
Exercise detail has 3 components
Detail, similar exercise and exercise videos
For home we are using two state exercise which contains data for all the exercise and bodypart which contains various bodyparts which we are fetching from the api
data.map(item)=>(to loop over data)
data.filter((item)=> item.name.toLowerCase().includes(search)||item.bodyPart.toLowerCase().includes(search))
To get the id from the url we used useparams hook to get the id for the detail we have to show
For hosting the website i used netlify and the live link is given below.

# 2.Description

I have a keen interset in fitness and i like working out but as i couldnt afford a trainer it was difficult for me to start as i didnt knew proper exercise and their forms so from that only i thought of creating an exercise library
Tech stack used is reactjs,rapid api which is basically a website for collection of different apis  from which i have used exercise database and inline css and material ui for frontend and interactive user interface.
The user can search a particular body part or exercises and for the corresponding keyword,the system would fetch the details of the exercise and user would see the exercises related to their requierements and their proper form.



# 3.Input Output
In the search bar if we give an exercise as input and we get the output correspnding to it.

Input:
![image](https://user-images.githubusercontent.com/21967832/208240952-b959418d-b6a0-4fdd-aa34-4f306e7f157f.png)


![image](https://user-images.githubusercontent.com/21967832/208240944-ace8a58a-2621-4964-825f-5cc71582434a.png)


# 4.Live Link:
https://playful-banoffee-211cb0.netlify.app

# 5.Screenshot of the Interface
![image](https://user-images.githubusercontent.com/21967832/208240970-48d7605b-464f-4aac-a192-56d0abf388ab.png)

![image](https://user-images.githubusercontent.com/21967832/208240973-8f884e1c-94e3-4bc8-ba0d-c14994637e23.png)

![image](https://user-images.githubusercontent.com/21967832/208240980-8366d344-422f-4ab7-9a10-e134a00a1f78.png)







