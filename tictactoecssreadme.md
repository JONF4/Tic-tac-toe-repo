#Tictactoe.css

*{
background-color: black;
color: white
}

.game-title{
    Color: #0202abc7;
    font-size: 100px; 
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    line-height: 60px;
    padding-left: 200px;
}

.game--status{
    color: white;
    font-size:30px;
     padding-left: 20px;
     margin-bottom: 100px;
}

.box-container{
    display:grid;
    grid-template-columns: repeat(3, auto);
    width: 306px;
    margin: 50px auto;
   
    
    
}
.cell{
    color: white;
    text-align: center;
    font-family: cursive;
    font-size: 60px;
    border: 2px solid;
     width: 100px;
     height: 100px;
     line-height: 100px;
     cursor:pointer;
     background-color:rgb(3, 23, 177);
     box-shadow: black;
     border-radius: 12px;
      
}

/* This entire code from line 50 onwards is intended to make the button appear 3D*/

.restart-btn{
    background: #938af3;
    border-radius: 12px;
    border: none;
    padding: 0;
    cursor: pointer;
   margin:0px
    
  }

  .refresh-btn{
    background: rgb(2, 35, 201);
    border-radius: 12px;
    border: none;
    padding: 0;
    cursor: pointer;
    margin:0px;
    margin-left: 300px;
   
  }
    


  .restart-front {
    padding: 12px 42px;
    border-radius: 12px;
    font-size: 3rem;
    background: rgb(77, 72, 206);
    color: white;
    transform:translateX(6px);
  
  }

  .front {
   
    padding: 12px 42px;
    border-radius: 12px;
    font-size: 3rem;
    background: rgb(0, 124, 240);
    color: white;
    transform:translateX(-6px)
  }

.restart-btn, .refresh-btn{
  display: inline-block;
}

.restart-front, .front{
  display: inline-block;

}
