# My Future Career and Goals

## __My Current Position at MIZZOU__:


As of March 2022 I am a Junior at the University of Missouri-Columbia. I started my journey at MIZZOU as a Business Administration Major. 

I recently switched to Information Technology fall of 2021. I Obtained a Minor in business before switching to Information Technology.

I chose to not further my academics in business because the kind of job I wanted was not offered in that field. I was more interested in a job like

a software engineer which is my ideal career choice. I should be able to graduate from Mizzou in the summer of 2023.


![Mizzou](https://user-images.githubusercontent.com/97974825/158626171-9c42c1f5-19bd-46ee-9623-2004ba94ff8b.jpg)


## __What do I aim to Accomplish in My Ideal Career?__

I aim to accomplish a career that I can grow with and enjoy at the same time. I always enjoyed and had a knack to solving puzzles which is

offered in the Information Technology feild of study. Technology is the foundation of our society and will be a neccesity for generations to come.

Already in my limited time in the technology department I learned a great deal and enjoy every ounce of knowledge I gained. 

I aim to be a contributing factor to a large company and eventually use that knowledge to build my own business.


![office](https://user-images.githubusercontent.com/97974825/158627439-ca2c00b4-5242-4ca6-bf6e-f12803103b06.jpg)

## *My FIZZBUZZ Code Block*

```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
    var fizzhold ="";
	var displayHTML = "";
	for (i = 1; i < 101; i++) {
		if (i % 3 === 0 && i % 5 === 0)
        {
            console.log("FizzBuzz");
            fizzhold ="FizzBuzz";
        } 
        else if (i % 5 === 0) 
        {
            console.log("buzz");
            fizzhold ="Buzz";
        } 
        else if (i % 3 === 0) 
        {
            console.log("fizz");
            fizzhold ="Fizz";
        } 
        else {
            console.log(i);
            fizzhold ="";
        }
	    displayHTML += "<p>" + i + ":" + fizzhold + "</p>";
    }
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```
[**Return to Home**](README.md)
