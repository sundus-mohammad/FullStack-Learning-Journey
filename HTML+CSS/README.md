<!DOCTYPE html>
<html lang="en"

style="background-color: rgb(253, 223, 238) ; color: rgb(108, 33, 75);"> 

<head> 

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FirstApp</title>
  <h1>Training Page </h1>
 
  <style>   
  
    table {
     width : 100%;
     background-color: rgb(246, 252, 255) ;
     color: rgb(252, 252, 252);
     border-spacing: 2px ;
     border-color: rgb(255, 255, 255);
     vertical-align: middle;
    }  

    th{
     background-color: rgb(120, 37, 72);
     height: 40px ;
    }

    td{
     background-color: rgb(179, 87, 133);
     height: 30px ;
     text-align: center;
    } 

    button  {
     background-color:white);
     color: rgb(97, 20, 47);
    }
    
    .submit-btn{
     background-color:white;
     color: rgb(97, 20, 47);
    }

    select{
      background-color: white ;
      color: rgb(128, 28, 70); 
    }

    img {
      height: 400px;
      width: 100 ;
      border-radius: 24px;
      margin: 50px;
    }

    img{
      transition:0.1s;
    }

    img:hover{
     transform: scale(1.05);
    }

    
  </style>
</head>

<body>

  <img src="https://images.pexels.com/photos/12569113/pexels-photo-12569113.jpeg?auto=compress&cs=tinysrgb&h=627&fit=crop&w=1200alt="">

   <h3>welcome to my first project</h3>
  
   <form>
   <lable for="username"> Name : </lable>

   <input type="userName"
     placeholder="enter your name"
     width: 200px;
     pattern="[A-Za-z]{20}"
    > 
 
   <br><br>

   <lable for="number1"> Phone Number : </lable>

   <input type="number1" 
     placeholder="+962XXXXXXXX"
    >

   <br><br>

   <label class="" for=""name" class="requiredFields"> National No :</label>
  
   <input type ="text" id="nameEN" 
     name="name2"
     required
     class="requiredFields"
     max=""
     min=""
     pattern="[A-Za-z]{3,}"
     title="name must be at least 3 letters long and contain only letters."
     placeholder="enter your national number"
     width: 200px;
    >

   <br><br>

    <label for="age">Age : </label>
    <input type="namber"
     placeholder="enter your age" 
     pattern = "[0-9]{1,2}"
     width: 200px;
    >

   <br><br>

   <lable for="email"> Email : </lable> 

   <input type="email"
     placeholder="enter your email"required
     width: 200px;
    >

    <br><br>
    <lable for="country"> Country : </lable>
    <select name="country">
     <option value="" disabled selected>Select your country</option>
     <option value="jordan"> jordan </option>
     <option value="saudia arabia"> saudia arabia </option>
     <option value="iraq"> iraq </option>
    </select>

    <br><br>

   <input  
     type="submit"
     value="send data"
     class="submit-btn"
     width: 200px;
    >

  </form>

  <br><br><br><br>

  <table>
     <thead>
       <tr>
       <th> name </th>
       <th>phone</th>
       <th> email </th>
      </tr>
    </thead>

    <tbody>
     <tr>
        <td>sundus</td>
        <td>0782083600</td>
        <td>sundus3764@gmail.com</td>
      </tr>

      <tr>
       <td>mohammad</td>
        <td>077349277</td>
        <td>mohammsd37364@gmail.com</td>
      </tr>

    </tbody>

  </table>

  <br><br>

  <button> Edit  </button>
  <button> Delete </button>

  <br><br><br>

  <div>
    <form>
      <label>Name2 </label>
      <input type="text">
      <br><br>
      
      <label>phone2 </label>
      <input type="tel">
      <br><br>
      
      <button type="submit"> submit </button>
    </form>
  </div>


</body>
</html>
