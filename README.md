<!DOCTYPE html>
<html lang="en">
<head>
 
  
</head>
  
  <body text="green">
    
   <center> <p id="new"><h2>Ms dhoni</h2></p> <br>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_VaA1PJudTstJbr03EWbRaMLA8z1vgyfNL2kQpLvFQjRGMjrjZ2JgXMWK2UPd813Lba0&usqp=CAU"><br><br><br>
     <button class="glow-on-hover" type="button" id="button" onclick="newtext()">GET MORE INFO!</button><br><br><br><label id="label"></label><br><br><br><br>
     <script>
        
     function newtext() {
      document.getElementById("label").innerHTML="Dhoniiiii finishes off in style. A magnificent strike into the crowd. India lift the World Cup after 28 years. The party's started in the dressing room. And it’s an Indian captain, who’s been absolutely magnificent, in the night of the final.M.S. Dhoni, in full Mahendra Singh Dhoni, (born July 7, 1981, Ranchi, Bihar [now Jharkhand] state, India), Indian cricketer whose rise to prominence in the early 21st century culminated in his captaincy of the Indian national team that won the one-day Cricket World Cup in 2011.Dhoni made his international debut in 2004. His talent with the bat came to the fore in an innings of 148 runs against Pakistan in his fifth international match. Within a year he joined the India Test team, where he quickly established himself with a century (100 or more runs in a single innings) against Pakistan. Despite his inexperience, Dhoni took over the captaincy of the one-day side in 2007 and led India to the Twenty20 (T20) world title. Series wins over Australia and Sri Lanka, among others, moved India to the top of the International Cricket Council (ICC) Test rankings for the first time in December 2009. Dhoni was honoured for his play with the ICC One Day International Player of the Year Award in 2008 and 2009. In the 2011 one-day World Cup, Dhoni’s dashing innings of 91 not out—in front of a home crowd in Mumbai—paved the way for India’s victory over Sri Lanka in the final. He also led India to an appearance in the semifinals of the 2015 Cricket World Cup. Dhoni stopped serving as India’s captain in 2017, having led his country in 331 international matches, the most for a captain in the sport’s history.Mahendra Singh Dhoni or MS Dhoni is an Indian International Cricketer who has recently retired from International Cricket. He is an Indian International cricketer who captained the Indian National Team in the limited over formats and in Test Cricket from 2007-2016 and 2008-2014 respectively. MS Dhoni is the only captain in the history of Cricket to win all the ICC trophies.MS, Mahi, MSD, Thala, Captain Cool, Mahendra Singh Dhoni! Footballer in school, later Traveling Ticket Examiner, Cricketer, Army man, Businessman! The more things seem clear about Dhoni, the more enigmatic (even Bharat Sundaresan couldn’t unravel much in his book, as he himself accepted in the closing chapters) he remainsAll these qualities kept paying rich dividends for him, the team and the country. The acme of it all – the night of 2nd April 2011 – lifting the World Cup after 28 yearsThe Indian cricket team won the 2011 Cricket World Cup under his captainship. His Test cricket and One Day International records are the best among all Indian captains to date. He took over the ODI captaincy from Rahul Dravid in 2007 and led the team to its first ever inter-country ODI series wins in Sri Lanka and New Zealand. Dhoni also holds the post of Vice-President of India Cements Ltd. after resigning from Air India. India Cements is the owner of the Indian Premier League team Chennai Super Kings, and Dhoni has been its captain since the first edition of IPL.[5][6]"

      }
     
    
     </script>
     <style>
     html,
body {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100vh;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    background:#000;

}
input{
    border-radius: 15px;
    font-size: 20px;
    height: 20px;
    width: 500px;
}

.glow-on-hover {
    width: 220px;
    height: 50px;
    border: none;
    outline: none;
    color: #fff;
    background: #111;
    cursor: pointer;
    position: relative;
    z-index: 0;
    border-radius: 10px;
}

.glow-on-hover:before {
    content: '';
    background: linear-gradient(45deg, #ff0000, #ff7300, #fffb00, #48ff00, #00ffd5, #002bff, #7a00ff, #ff00c8, #ff0000);
    position: absolute;
    top: -2px;
    left:-2px;
    background-size: 400%;
    z-index: -1;
    filter: blur(5px);
    width: calc(100% + 4px);
    height: calc(100% + 4px);
    animation: glowing 20s linear infinite;
    opacity: 0;
    transition: opacity .3s ease-in-out;
    border-radius: 10px;
}

.glow-on-hover:active {
    color: #000
}

.glow-on-hover:active:after {
    background: transparent;
}

.glow-on-hover:hover:before {
    opacity: 1;
}

.glow-on-hover:after {
    z-index: -1;
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    background: #111;
    left: 0;
    top: 0;
    border-radius: 10px;
}

@keyframes glowing {
    0% { background-position: 0 0; }
    50% { background-position: 400% 0; }
    100% { background-position: 0 0; }
}</style>


  </body>
</html>
