	
			         	Pseudo Element
h1::first-letter
p::first-line

adjacent sibling - of parent but it depends on context
sibling comes right after it
h3 + p::firstline

//Parent element
.post-header{
	position: relative; // dont forget
}
h2{
	background-color: green;
}

// Child Element
h2::after{
	content: "TOP";
	position: absolute;
	font-size: 16px;
	font-weight: bold;	
	display: inline-block;
	padding: 5px 10px;
	color: #444;

	// Negative Value - move opposite direction
	top: -10px
	right: -25px
}