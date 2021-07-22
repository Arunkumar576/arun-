
<!DOCTYPE html>
<html>
    <head>
        <title>

        </title>
        <link rel="stylesheet" href="css/style.css">
    </head>
    <body>
        
        <div class="background">
            <div class="nav">
                <a   class="a active" href="#">HOME</a>
                <a class="b" href="#">ABOUT US</a>
                <a class="c" href="#">GALLERY</a>
                
            </div>
            <div class="content">
                <div class="home">
                    <h1>VICRAM</h1>
                    <H3>My favourite celebrity</H3>
                </div>
                <div class="aboutus">
                    <h3>VICRAM (acter)</h3>
                    <p>
                        Kennedy John Victor (born 17 April 1966), better known by his stage name Vikram, is an Indian actor and playback singer who predominantly appears in Tamil language films and also appered in Telugu, Malayalam and Hindi films. He is among the most decorated actors in Tamil cinema, with awards including seven Filmfare Awards South, a National Film Award and a Tamil Nadu State Film Award. Amongst his other honours include the Kalaimamani Award from the Government of Tamil Nadu in 2004 and an honorary Doctorate by the Popular University of Milan[3][4][5] in May 2011. Based on the earnings of Indian celebrities, Vikram was included in the Forbes India Celebrity 100 list for 2016 and 2018.[6] He did several variety roles in his films, and he is among the prolific actors in Tamil .</p> <br>
                        <p>

Vikram made his debut in the 1990 film En Kadhal Kanmani, which was followed by a series of small-budget Tamil, Malayalam and Telugu films in the 1990s, many of which went unnoticed. However, the success of Bala's tragedy film Sethu (1999), in which Vikram appeared as a rogue turned lover, started Vikram's successful career as an actor. In the early 2000s, Vikram appeared in a series of masala films, with Dhill (2001), Gemini (2002), Dhool (2003) and Saamy (2003). During the period, Vikram also appeared in diverse roles of disadvantaged people, including Kasi (2001), Samurai (2002) and Pithamagan (2003); the latter saw him win the National Film Award for Best Actor.[8] Vikram achieved further success in Anniyan (2005), Kanthaswamy (2009), Raavanan (2010) and Deiva Thirumagal (2011). Starring in the romantic thriller I (2015), Vikram won rave reviews from critics for his performance.

</p> <br> <p> Vikram has promoted various social causes and appeared as the Youth Envoy for the United Nations Human Settlements Programme in 2011. He has been a brand ambassador of Sanjeevani Trust and a school for special children, Vidya Sudha, which he stayed at during the making of Deiva Thirumagal as well as having long-term associations with the Kasi Eye Care and running his own welfare association through the Vikram Foundation.[9] In 2016, he produced and directed the video to the flood relief anthem, Spirit of Chennai, as a tribute to the city's volunteers following the 2015 South Indian floods.
                    </p>
                </div>
                <div class="gallery">
        
                    
        <div class="image"> 
        
            <img src="images/OIP (1).jpg" / >
        </div>
        <div class="image"> 
            <img src="images/OIP (2).jpg"  />
        </div>
        <div class="image"> 
            <img src="images/OIP (3).jpg" />
        </div>
        <div class="image"> 
            <img src="images/OIP (8).jpg" />
        </div>
        <div class="image"> 
            <img src="images/OIP (5).jpg" />
        </div>
        <div class="image"> 
            <img src="images/OIP (6).jpg" />
        </div>
        <div class="image"> 
            <img src="images/OIP (7).jpg" />
        </div>
        <div class="image"> 
            <img src="images/OIP (8).jpg" />
        </div>
        <div class="image"> 
            <img src="images/OIP (9).jpg" />

        </div>
        <div class="image"> 
            <img src="images/OIP (10).jpg" />
        </div>
        <div class="image"> 
            <img src="images/OIP (11).jpg" />
        </div>
                </div>
            </div>

        </div>
        <script type="text/javascript" src="js/jquery-3.6.0.js"></script>
        <script text="text/javascript">
        $(document).ready(function(){
            $('a').click(function(){
               // alert("i am click")
               var selected= $(this);
               $('a').removeClass('active');
               $(selected).addClass('active');

            });
            var $a=$('.a'),
            $b=$('.b'),
            $c=$('.c'),
            $d=$('.d'),
            $home=$('.home'),
            $aboutus=$('.aboutus'),
            $gallery=$('.gallery'),
            $contactus=$('.contactus');
        

            $a.click(function(){
                $home.fadeIn();
                $aboutus.fadeOut();
                $gallery.fadeOut();
                $contactus.fadeOut();
            });
            $b.click(function(){
                $aboutus.fadeIn();
                $home.fadeOut();
                
                $gallery.fadeOut();
                $contactus.fadeOut();
                
                
            });
            $c.click(function(){
                $gallery.fadeIn()
                $home.fadeOut();
                $aboutus.fadeOut();
                
                $contactus.fadeOut();
                
                
            });
            $d.click(function(){
                $contactus.fadeIn();
                $home.fadeOut();
                $aboutus.fadeOut();
                $gallery.fadeOut();
               
                
                
            });
        });
         </script>
    </body>
</html>
