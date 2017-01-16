# css-rotate-heart-

<!DOCTYPE html>
<html>
<head>
	<link rel='stylesheet' href='style.css'/>
	p {
	color: #f06;
	font: italic 200% Georgia, serif;
	transition: 1s cubic-bezier(.2,.6,.8,.8);
	width:300px;
}

#vid:hover .heart {
    transform: rotateY(360deg);
    }
    
#vid{
      font-size:100px;  
      text-align:center;  
        }
</head>
<body>
<div id ="vid"><p class="heart">&hearts;<p></div>
</body>
</html>
