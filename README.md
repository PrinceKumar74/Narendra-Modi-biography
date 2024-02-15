<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project-1 || Narendra Damodardas Modi</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <div class=" container">
        <div class="content">
            <section class="top_section">
                <div class="image_container">
                    <img src="/Prime_Minister_Narendra_Modi_Portrait.png" alt="Narendra Damodardas Modi" />
                </div>
                <div>
                    <h1>Narendra Damodardas Modi</h1>
                    <h4>born 17 September 1950</h4>
            </section>
            <section class="about_section">
                <h2> Prime Minister of India</h2>
                <p> <b>Narendra Damodardas Modi (Gujarati:
                        [ˈnəɾendɾə dɑmodəɾˈdɑs ˈmodiː] ⓘ;</b> born 1
                    7 September 1950)[b] is an Indian politician
                    who has served as the 14th prime minister of
                    India since May 2014. Modi was the chief minister
                    of Gujarat from 2001 to 2014 and is the Member
                    of Parliament (MP) for Varanasi. He is a member
                    of the Bharatiya Janata Party (BJP) and of the
                    Rashtriya Swayamsevak Sangh (RSS), a right wing
                    Hindu nationalist paramilitary volunteer organisation.
                    He is the longest-serving prime minister from outside
                    the Indian National Congress.</p>
            </section>
            <section class="biography-section">
                <h3>Biographies</h3>
                <ul>
                    <li>Narendra Damodardas Modi was born on 17 September 1950 </li>
                    <li>Gujarati Hindu family of grocers in Vadnagar, </li>
                    <li>Mehsana district, Bombay State (present-day Gujarat).</li>
                    <li>He was the third of six children born to Damodardas Mulchand Modi</li>
                    <li>( c. 1915–1989) and Hiraben Modi (1923–2022).</li>
                </ul>
            </section>
            <footer>
                <p>https://en.wikipedia.org/wiki/Narendra_Modi
                    <a href="https://en.wikipedia.org/wiki/Narendra_Modi">wikipedia</a>
                </p>
            </footer>
        </div>
    </div>
</body>

</html>

                     <!--CSS FILE START-->

*{
    margin: 0%;
    padding: 0%;
    box-sizing:border-box;
}
.container{
      background-color:#e5e5fd ;
      min-height: 100vh;
      border: 10px solid #1d1e4c;
 }

  .content{
    max-width: 900px;
    margin: 0 auto;
  }
  .top_section{
    margin: 40px;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  }
  .top_section h1{
    font-size: 30px;
font-weight: bold;
color: #1d1e4c;
text-transform: uppercase;
  }
 .top_section h4{
   text-align: end;
   font-size: 20px;
}
  .image_container,img{
   width: 200px;
   height: 220px; 
   border-radius:50%;

  }
  .about_section{
    margin: 50px; ;
  }
  .about_section h2{
    font-size: 70px;
    font-weight: 400;
    margin-bottom:20px ;
  }
  .about_section p{
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 1.2px;
    text-align: justify;
  }
  .biography-section{
    margin: 50px 0;
  }
  biography-section h3{
    margin-bottom: 20px;
  }
.biography-section ul{
    margin-left:50px ;
}
biography-section li{
    margin-bottom: 15px;
}
footer{
    margin: 50px 0 ;

}
footer p{
 text-align: end;
}





































































































