input.error { 
    box-shadow: 0 0 8px 4px #ff0000;
} 
label.error { 
    color: #ff0000;
    font-weight: normal;
    margin-left: 50px;  
}

body{
    margin: 250px auto 0 auto;
    width: 375px;
    height: 812px;
}

.Container {
    margin: 250px auto 0 auto;
    text-align: center;
    width: 375px;
    height: 812px;
    padding-bottom: 20px;
}

#name,#surname,#date,#email,#phone,#password {
position: relative;
margin-top: 40px; 
width: 300px;
height: 40px;
background: #dbaef5;
left: calc(50% - 300px/2 - 3.5px);
border: 1px solid rgba(113, 113, 113, 0.5);
border-radius: 20px;
font-family: Georgia;
font-style: normal;
font-weight: 300;
font-size: 20px;
align-items: center;
color: #696969;
padding-left: 17px;

}

form { 
background-image: url(clouds.jpg);
position: absolute;
width:  375px;
height: 800px;
}

button {
position: absolute;
width: 300px;
height: 40px;
left: calc(50% - 300px/2 + 0.5px);
bottom: 150px;
border-radius: 20px;
background: #844cf5;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

entr {
position: absolute;
width: 208px;
height: 25px;
left: calc(50% - 90px/2 - 0.5px);
bottom: 5px;
font-family: Georgia;
font-style: normal;
font-weight: normal;
font-size: 30px;
line-height: 35px;
display: flex;
align-items: center;
text-align: center;
color: #0008ff;
}
.dws-input input:hover {
    box-shadow: 0 0 5px 4px #844cf5;
}
