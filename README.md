# Tribute
![](free.jpg)
![](freecode1.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tribute Page</title>
    <link rel="stylesheet" href="freecode.css" />
</head>
<body>
    <main>
    <h1 id="title">Dr. Norman Borlaug</h1>
    <p >The man who saved a billion lives.</p>
    <div id="image-div">
        <img id="image" src="free.jpg" />
        <p id="img-caption">Dr. Norman Borlaug, third from the left, trains biologists in Mexico on how to increase wheat yields - part of his life-long war on hunger.</p>
    </div>
    <h2>Here's a time line of Dr. Borlaug's life:</h2>
    <p id="tribute-info">
        <ul>
            <li><span>1914</span> - Born in Cresco, Iowa</li>
            <li><span>1933</span> -  Leaves his family's farm to attend the University of Minnesota, thanks to a Depression era program known as the "National Youth Administration"</li>
            <li><span>1935</span> - Has to stop school and save up more money. Works in the Civilian Conservation Corps, helping starving Americans. "I saw how food changed them", he said. "All of this left scars on me."</li>
            <li><span>1937</span> - Finishes university and takes a job in the US Forestry Service</li>
            <li><span>1938</span> - Marries wife of 69 years Margret Gibson. Gets laid off due to budget cuts. Inspired by Elvin Charles Stakman, he returns to school study under Stakman, who teaches him about breeding pest-resistent plants.</li>
            <li><span>1941</span> - Tries to enroll in the military after the Pearl Harbor attack, but is rejected. Instead, the military asked his lab to work on waterproof glue, DDT to control malaria, disinfectants, and other applied science.</li>
            <li><span>1942</span> - Receives a Ph.D. in Genetics and Plant Pathology</li>
            <li><span>1944</span> - Rejects a 100% salary increase from Dupont, leaves behind his pregnant wife, and flies to Mexico to head a new plant pathology program. Over the next 16 years, his team breeds 6,000 different strains of disease resistent wheat - including different varieties for each major climate on Earth.</li>
            <li><span>1945</span> -  Discovers a way to grown wheat twice each season, doubling wheat yields</li>
            <li><span>1953</span> - crosses a short, sturdy dwarf breed of wheat with a high-yeidling American breed, creating a strain that responds well to fertilizer. It goes on to provide 95% of Mexico's wheat.</li>
            <li><span>1962</span> - Visits Delhi and brings his high-yielding strains of wheat to the Indian subcontinent in time to help mitigate mass starvation due to a rapidly expanding population</li>
            <li><span>1970</span> -  receives the Nobel Peace Prize</li>
            <li><span>1983</span> - helps seven African countries dramatically increase their maize and sorghum yields</li>
            <li><span>1984</span> - becomes a distinguished professor at Texas A&M University</li>
            <li><span>2005</span> - states "we will have to double the world food supply by 2050." Argues that genetically modified crops are the only way we can meet the demand, as we run out of arable land. Says that GM crops are not inherently dangerous because "we've been genetically modifying plants and animals for a long time. Long before we called it science, people were selecting the best breeds."</li>
            <li><span>2009</span> - dies at the age of 95.</li>
        </ul>
    </p>
    <p id="pm">
        "Borlaug's life and achievement are testimony to the far-reaching contribution that one man's towering intellect, persistence and scientific vision can make to human peace and progress."
    </br>
        <div id="name">-- Indian Prime Minister Manmohan Singh</div>
    </p>
    <p id="tribute-link">
        If you have time, you should read more about this incredible human being on his <a href="https://en.wikipedia.org/wiki/Norman_Borlaug" target="_blank">Wikipedia entry</a>
    </p>
    </main>
</body>
</html>
![](freecode.css)
main{
    background-color: rgb(180,180,180);
}

#title {
    text-align: center;
    background-color: rgb(180,180,180);
    padding: 50px 50px 5px 50px;
    font-family: sans-serif;
    font-size: 40px;
}

p {
    text-align: center;
    font-family: sans-serif;
    background-color: rgb(180,180,180);
}

#image {
    padding: 100px 100px 5px 150px;
}

h2 {
    text-align: center;
    padding-top: 50px;
}

ul {
    padding-top: 30px;
    padding-left: 400px;
    padding-right: 300px;
}

span {
    font-weight: bold;
}

li {
    padding: 10px;
}

#pm {
    padding-right: 300px;
    padding-left: 300px;
    padding-top: 20px;
}

#tribute-link {
    font-weight: bolder;
    font-size: larger;
}

#name {
    padding-left: 300px;
}
