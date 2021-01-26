
<html>
    <head>
<link rel="stylesheet" type="text/css" href="stylesheet.css">
	    <style>body {
font-family: Courier New, Verdana, Arial;
background-color: black;
color: white;
margin:30px;
background-image:
url("https://variety.com/wp-content/uploads/2020/02/friends.jpg?w=681&h=383&crop=1");
background-repeat: no-repeat;
background-attachment: scroll;
background-position: center;
padding-top: 50px;

}


h1 {
background-color: black;
font-size: 100px;
border: 10px;
border-color: red;
border-style: dashed;
text-align: center; 
letter-spacing: 20px;
 }


h2, h3 
{
font-size: 60;
text-decoration: aqua wavy underline;
font-style: italic;
text-align: center;
padding-bottom: 20px;

}

.friends {
font-size: 25px;
direction: ltr;
text-indent: 30%;
word-spacing: 10px;

}

A:link { color: red; 
text-decoration:none;
background-color:gray;

}
A:visited { color: aqua} 
A:hover { color: yellow; } 

table
{color:red

  }


ol {
list-style: none;
text-align: center;
border: 1px;

}

li {
border-color: white;
border-style: dotted;
border-left-style:solid;
border-right-style:solid;
border-left-width: 4px;
border-right-width: 4px;
}




 
	    </style>
        <title>Friends: Antonia Koscak i Gabriela Dud (Seminarski rad iz kolegija Programski alati II)</title>
        <script src="java.js">
	    window.onload =  function() {
 document.getElementById("charachters").innerHTML = "Main characters:";
};
    date=new Date()
        document.write("Today is " + date)

function firstFunction() {
  alert("Real name: David Schwimmer");
}
function secondeFunction() {
  alert("Real name: Courteney Cox");
}
function thirdFunction() {
  alert("Real name: Matt LeBlanc");
}
function fourthFunction() {
  alert("Real name: Jennifer Aniston");
}
function fifthFunction() {
  alert("Real name: Lisa Kudrow");
}
function sixthFunction() {
  alert("Real name: Matthew Perry");
}


function provjera_duzine(duzina_unosa){
 var duzina =
document.actor.tekst.value.length;
 if (duzina >= 3){
    alert("Friends says 'Hello'.");
 }
 else {
    alert("Smelly cat");
 }
}</script>
       

    </head>
    <body>
        <h1>FRIENDS</h1>
        <hr>
<div class="container">
        <div class="meni">
		<div class="zaglavlje"><button onclick="show()">About</button></div> 
<br>            <div class="zaglavlje"><button onclick="show()">Menu</button></div>  
<br>            <div class="zaglavlje"><button onclick="show()">Information</button></div>

        </div>
<div>
      <p class="friends">Friends is an American television sitcom, created by David Crane and Marta Kauffman, which aired on NBC from September 22, 1994, to May 6, 2004, lasting ten seasons.[1] With an ensemble cast starring Jennifer Aniston, Courteney Cox, Lisa Kudrow, Matt LeBlanc, Matthew Perry and David Schwimmer, the show revolves around six friends in their 20s and 30s who live in Manhattan, New York City. The series was produced by Bright/Kauffman/Crane Productions, in association with Warner Bros. Television.</p>
      <br>

      <p id="charachters">    </p>
       <button onclick="firstFunction()">Ross</button>
       <button onclick="secondeFunction()">Monica</button>
       <button onclick="thirdFunction()">Joey</button>
       <button onclick="fourthFunction()">Rachel</button>
       <button onclick="fifthFunction()">Phoebe</button>
       <button onclick='sixthFunction()'>Chandler</button>
     <br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>  
<br>
<br>
<br>
<br>  
<br>
<br>
<br>  
<br>
<br>
<br>
<br>
       <h2>Seasons:</h2>

       <ol type="1.">
 <li>Season one (1994 - 1995)</li>
 <li>Season two (1995 - 1996)</li>
 <li>Season three (1996 - 1997)</li>
 <li>Season four(1997 - 1998)</li>
 <li>Season five (1998 - 1999)</li>
 <li>Season six (1999 - 2000)</li>
 <li>Season seven (2000 - 2001)</li>
 <li>Season eight (2001 - 2002)</li>
 <li>Season nine (2002 - 2003)</li>
 <li>Season ten (2003 - 2004)</li>
       </ol>
       <br>
       <h2>Best moments on TV show</h2>
       <p class="friends">It's been over 20 years since top TV show, Friends hit the small screen. Our lives got a whole lot funnier once Ross, Rachel, Monica, Phoebe, Chandler and Joey came into our lives. From Phoebe's Smelly Cat song to Ross' fake tan, the cherished characters have had us crying tears of laughter. The fabulous ensemble still grace our television screens and cheer us up to this very day...</p>

       <a href="https://www.youtube.com/watch?v=5e7bf3hW6lE&ab_channel=MadNessX1O">WHATCH HERE!</a>
       
      <br>
<form name="actor">
 <table>
 <tr>
 <td>Choose number:</td>
 <td>
 <input type="text" name="tekst"
 size="20">
 </td>
 </tr>
 </table>
 <p>
 <input type="submit" value="Unesi"
 onClick="provjera_duzine()">
</p>
</form>

<div id="footer">
</div>


    </body>
</html>
