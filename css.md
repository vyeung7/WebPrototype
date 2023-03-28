Body{
  top:0;
  bottom:0;
  right:0;
  left:0;
  position: relative;
  font-family: sans-serif;
  background-color: linen;
  color: #A47551;
}

ul{
	list-style-type:none;
	margin:0;
	padding:0;
	background-color: darkseagreen;
  text-align: center;
}

img style{
  display: block;
  margin-left: auto;
  margin-right: auto;
}
li{
  display: inline-block;
	float: center;
}

li a{
	float: left;
	text-align: center;
	padding: 20px 45px;
	text-decoration: none;
	font-family: serif;
	font-size: 20px;
  text-transform: uppercase;
	color: white;
  font-weight:bold;
  width: 100px;
  display: block;
}
li a:hover{
	color:darkseagreen;
	background-color:white;
}
h1{
  font-size: 40px;
}
section1{
  height: 60vh;

}




text{
  text-align: center;
  font-family: serif;
  width: 600px;
  margin-left:auto;
  margin-right: auto;
}

.image-grid{
  --gap: 16px;
  --num-cols: 3;
  --row-height: 300px;

  box-sizing: border-box;
  padding: var(--gap);

  display: grid;
  grid-template-columns: repeat(var(--num-cols), 1fr);
  grid-auto-rows: var(--row-height);
  gap: var(--gap);
}

.image-grid > img{
  width:100%
  height:100%
  object-fit: cover;
}

divider{
  width: 300px;
  height: 5px;
  background-color: khaki;
  display: inline-block;
  border-radius: 50%
}
h2{
  background-color: #AB6B51;
  color: white;
  text-align: center;
}

h3{
  background-color: #B1C7CB;
  color: white;
  text-align: center;
}

h4{
  background-color: #6C614A;
  color: white;
  text-align: center;
}
