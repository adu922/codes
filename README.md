slip 1:
<!DOCTYPE html> 
<head> 
 <style> 
 .form { 
 
 height:350px; 
 width:350px; 
 text-align: center; 
 background-color: rgb(50, 200, 240); 
 } 
 button { 
 background: rgb(11, 200, 86); 
 } 
 #butt { 
 background:rgb(64, 136, 357); 
 
 } 
 
 
 </style> 
 <title>Project Management</title> 
</head> 
<body><center>
 <h2><u>Project Management</u></h2><br> 
 <div class="form"> 
 
 
 <label for="name"><b>Project Name</b></label> 
 <input type="text"  placeholder="Project Name"><br><br> 
 
 <label for="name"><b> Assigned to</b></label> 
 <select><option value="volvo">Er Merry Pelision</option></select><br><br> 
 
 <label for="start"><b>Start date:</b></label> 
 <input type="date"> <br><br> 
 
 <label for="start"><b>End date:</b></label> 
 <input type="date"> <br><br> 
 
 <label for="name"><b> Priority</b></label> 
 <input type="radio"> 
 <label for="html"><b>High</b></label> 
 <input type="radio"> 
 <label for="html"><b>Average</b></label> 
 <input type="radio"> 
 <label for="html"><b>Low</b></label> 

 <br><br> 
 
 <label for="description" id="desc"><b>Description</b></label> 
 <input type="text" ><br><br> 
 
 <button type="button">Submit</button> 
 <button type="butt" id="butt"> Clear</button> 
 
 </form> 
 </div> 
</center>
</body> 
</html> 

import pandas as pd
import matplotlib.pyplot as plt
iris = pd.read_csv('D:\Iris.csv')
ax=plt.subplots(1,1,figsize=(10,8))
iris['Species'].value_counts().plot.pie(explode=[0.1,0.1,0.1],autopct='%1.1f%%',shadow=True,figsize=(10,8))
plt.title("Iris Species %")
plt.show()

import pandas as pd
data = pd.read_csv('D:\winequalityN.csv')
 print(data.describe())


