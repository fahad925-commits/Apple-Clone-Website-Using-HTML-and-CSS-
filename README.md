<!DOCTYPE html>
<html lang="en">

<head>
   *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
#navbar{
    display:flex;
    justify-content: center;
    gap:  40px;
    padding:20px 0px  ;
    background-color:white;
    color: black;
    
}
#navbar li{
 list-style: none; 
}  
button{
     padding: 11px 21px;
    border-radius: 980px;
    font-size: 17px;
    font-weight: 600;
    margin:10px 0;
}
#section1{
    height: 650px;
    background-image: url("../Images/01.jpeg");
    display: flex ;
    text-align: center;
    align-items: center;
    flex-direction: column;
    min-width: 28px;
    color: black;
    gap: 10px;
    justify-content: start;
    font-size: larger;
    padding: 50px;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
     
}
#section1 h1{
    font-size: 48px;
    font-weight: 600;
}
#section1 h3{
    font-size: 24px;
    font-weight: 400;
}
.btn1{
    background: #0071e3;
    color: black ;
    padding: 11px 21px;
    border-radius: 50px;
    font-size: 17px;
    font-weight: 400;
} 

#section2{
     height: 650px;
    margin-top: 10px;
    margin-bottom: 10px;
    background-image: url(../Images/02.jpeg);
    display: flex ;
    text-align: center;
    align-items: center;
    flex-direction: column;
    min-width: 28px;
    color: black;
    gap: 10px;
    justify-content: start;
    font-size: larger;
    padding: 50px;
    align-content: center;
    background-position: center; 
}

#section2 h1{
    font-size: 48px;
    font-weight: 600;
}
#section2 h3{
    font-size: 24px;
    font-weight: 400;
}

.btn1{
    background: #0071e3;
    color: black ;
    padding: 11px 21px;
    border-radius: 50px;
    font-size: 17px;
    display: flex;
}
.btn2{
    background-color: transparent;
    color: #0071e3;
     border: 1px solid #0071e3;
     border-color: #0071e3 ;
    

}
.btngroup{
display: flex;
justify-content: center;
gap: 20px;
 font-size: 17px;
font-weight: 400;

}
.btn2:hover{
    background-color: #0071e3;
    color: white;
}
#section3{
    height: 650px;
    margin-top: 10px;
    margin-bottom: 10px;
    background-image: url(../Images/03.jpeg);
    display: flex ;
    text-align: center;
    align-items: center;
    flex-direction: column;
    min-width: 28px;
    color: black;
    gap: 10px;
    justify-content: start;
    font-size: larger;
    padding: 50px;
    align-content: center;
    background-position: center;
    background-repeat: no-repeat;
    background-color: rgb(245, 245, 247); 
}
#section3 h1{
    font-size: 48px;
    font-weight: 600;
}
#section3 h3{
    font-size: 24px;
    font-weight: 400;
}
#section4{
    display: flex;
    width: 100%;
    height: 650px;
    gap: 10px;
    background-position: center; 
    background-size: cover;

}
#section4left{
    width: 50%;
    background-image: url("../Images/ipad\ air.jpeg");
    background-size: cover;
    background-repeat: no-repeat;
    text-align: center;
    background-position: center;
    gap: 20px;
    padding: 0 20px;
}
#section4right{
    width: 50%;
    background-image: url("../Images/macbook.jpeg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    text-align: center;
    gap: 20px;
    padding:  0 20px;
}

.btn1{
    background: #0071e3;
    color: black ;
    padding: 10px 20px;
    border-radius: 50px;
    font-weight: 400;
    display: flex;
    gap: 10px;
}
.btn2{
    gap: 10px;
    background-color: transparent;
    color: #0071e3;
     border: 1px solid #0071e3;
     border-color: #0071e3 ;    
}
.btn2:hover{
    background-color: #0071e3;
    color: white;
}
#section4 h1{
    font-size: 48px;
    font-weight: 600; 
    /* gap: 10px; */
    
}
#section4 h3{
    gap: 10px;
    font-size: 24px;
    font-weight: 400;
}

#section5{
     display: flex;
    width: 100%;
    height: 650px;
    gap: 10px;
    background-position: center; 
    background-size: cover;
    padding: 10px;
    /* margin-top: 10px; */
  
}
#section5left{
    width: 50%;
    background-image: url("../Images/pick\ ipad.jpeg");
    background-size: cover;
    background-repeat: no-repeat;
    text-align: center;
    background-position: center;
    margin: 10px;
    gap: 20px;
}
#section5right{
    width: 50%;
    background-image: url("../Images/07.jpeg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    text-align: center;
    background-position: center;
    gap: 20px;
}

.btn1{
    background: #0071e3;
    color: black ;
    padding: 11px 21px;
    border-radius: 50px;
    font-size: 17px;
    font-weight: 400;
    display: flex;
}
.btn2{
    gap: 10px;
    background-color: transparent;
    color: #0071e3;
     border: 1px solid #0071e3; 
}
.btn2:hover{
    background-color: #0071e3;
    color: white;
}
#section5 h1{
    font-size: 48px;
    font-weight: 600;
     gap: 10px;
}
#section5 h3{
    gap: 10px;
    font-size: 24px;
    font-weight: 400;
}
#section6{
    display: flex;
    width: 100%;
    height: 650px;
    gap: 10px;
    background-position: center; 
    background-size: cover;
;

}
#section6left{
    width: 50%;
   /* height: 90vh; */
   align-items: center;
   justify-content: center;
    background-image: url("../Images/Trade\ In\ Work.jpeg");
    background-size: cover;
    background-repeat: no-repeat;
    text-align: center;
    background-position: center bottom;
}
#section6right{
    width: 50%;
    align-items: center;
    justify-content: center;
    background-image: url("../Images/Trade\ in\ Work\ 2.jpeg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center bottom;
    text-align: center;
}

.btn1{
    background: #0071e3;
    color: black ;
    padding: 11px 21px;
    border-radius: 50px;
    font-size: 17px;
    display: flex;
    gap: 10px;
}
.btn2{
    gap: 10px;
    background-color: transparent;
    color: #0071e3;
     border: 1px solid #0071e3;;    
}
.btn2:hover{
    background-color: #0071e3;
    color: white;
}
#section6 h1{
    font-size: 48px;
    font-weight: 600;
     gap: 10px;
}
#section6 h3{
    gap: 10px;
    font-size: 24px;
    font-weight: 400;
}

#footer {
    background-color: #333;
    width: 100%;
    height: 450px;
    color: #b1b1b3;
    border-bottom: 1px solid white;
}
.apple-footer {
    background-color: #161617;
    color: #f5f5f7;
    font-family: "SF Pro Text", "Helvetica Neue", Arial, sans-serif;
    padding: 40px 0;
    font-size: 12px;
}

.footer-content {
    max-width: 980px;
    margin: 0 auto;
    padding: 0 22px;
}

/* Legal text styles */
.footer-notes {
    color: #86868b;
    line-height: 1.5;
    margin-bottom: 20px;
}

.footer-notes hr {
    border: 0;
    border-top: 1px solid #424245;
    margin: 20px 0;
}

/* Grid Layout for Columns */
.footer-links-grid {
    display: flex;
    justify-content: space-between;
}

.footer-col h3 {
    color: #f5f5f7;
    font-size: 12px;
    font-weight: 600;
    margin-bottom: 10px;
    margin-top: 20px;
}

.footer-col ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

.footer-col ul li {
    margin-bottom: 8px;
}

.footer-col ul li a {
    color: #86868b;
    text-decoration: none;
    transition: color 0.3s;
}

.footer-col ul li a:hover {
    color: #f5f5f7;
    text-decoration: underline;
}

/* Bottom Legal Section */
.footer-bottom {
    margin-top: 35px;
    color: #86868b;
}

.footer-bottom a {
    color: #0066cc;
    text-decoration: none;
}

.footer-legal {
    display: flex;
    justify-content: space-between;
    padding-top: 15px;
}

.legal-links {
    display: flex;
    list-style: none;
    padding: 0;
}

.legal-links li {
    padding: 0 10px;
    border-right: 1px solid #424245;
}

.legal-links li:last-child {
    border-right: none;
}

.legal-links a {
    color: #86868b;
    text-decoration: none;
}

.country {
    margin-left: auto;
}
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Apple clone</title>
   <link rel="stylesheet" href="style.css">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
</head>

<body>
   <ul id="navbar">
      <li><i class="fa-brands fa-apple"></i></li>
      <li>Store</li>
      <li>Mac</li>
      <li>iPad</li>
      <li>iPhone</li>
      <li>Watch</li>
      <li>Vision</li>
      <li>Airpods</li>
      <li>Tv & Home</li>
      <li>Entertainment</li>
      <li>Accesories</li>
      <li>Support</li>
      <li><i class="fa-solid fa-magnifying-glass"></i></li>
      <li><i class="fa fa-shopping-bag" aria-hidden="true"></i></li>
   </ul>

   <div id="section1">
      <h1>iPhone</h1>
      <h3>Say hello to the latest generation of iphone. </h3>
      <div class="btngroup">
         <button class="btn1">Learn more</button>
         <button class="btn2">Shop iphone</button>
      </div>
   </div>

   <div id="section2">
      <h1>Air Pods Pro 3</h1>
      <h3>The world,s best in -era Active Noise Cancellation </h3>
      <div class="btngroup">
         <button class="btn1">Learn more</button>
         <button class="btn2">Shop</button>
      </div>
   </div>
   <div id="section3">
      <h1><i class="fa-brands fa-apple"></i>WATCH SERIES 11 </h1>
      <h3>Turn resolution into routines </h3>
      <h3>Quite quitting your fitness goals</h3>
      <div class="btngroup">
         <button class="btn1">Learn more</button>
         <button class="btn2">Shop</button>
      </div>
   </div>
   <div>
      <div id="section4">
         <div id="section4left">
            <h1>iPad air</h1>
            <h3>New super charged by m3 chip</h3>
            <div class="btngroup">
               <button class="btn1">Learn more</button>
               <button class="btn2">Shop</button>
            </div>
         </div>
         <div id="section4right">
            <h1>Mac Book Air</h1>
            <h3>Sky blue color</h3>
            <h3>Sky high performance with M4</h3>
            <div class="btngroup">
               <button class="btn1">Learn more</button>
               <button class="btn2">Shop</button>
            </div>
         </div>
      </div>
      <div>
         <div id="section5">
            <div id="section5left">
               <h1>ipad</h1>
               <h3>Now with the speed of A16 chip</h3>
               <h3>and double the starting storage</h3>
               <div class="btngroup">
                  <button class="btn1">Learn more</button>
                  <button class="btn2">Shop</button>
               </div>
            </div>
            <div id="section5right">
               <h1>HomePod mini</h1>
               <div class="btngroup">
                  <button class="btn1">Learn more</button>
                  <button class="btn2">Shop</button>
               </div>
            </div>
         </div>
         <div id="section6">
            <div id="section6left">
               <h1><i class="fa-brands fa-apple"></i>Trade in </h1>
               <h3>Get up to $180-$670</h3>
               <h3>in credit when you trade in</h3>
               <h3>iphone 13 or higher.'</h3>
               <div class="btngroup">
                  <button class="btn1">Learn more</button>
                  <button class="btn2">Shop</button>
               </div>
            </div>
            <div id="section6right">
               <h1><i class="fa-brands fa-apple"></i>Cards</h1>
               <h3>Get up to 3% daily cash back </h3>
               <h3>with every purchase</h3>
               <div class="btngroup">
                  <button class="btn1">Learn more</button>
                  <button class="btn2">Shop</button>
         </div>
            </div>
         </div>
          <footer class="apple-footer">
    <div class="footer-content">
        <section class="footer-notes">
           <ul>
            <li>1. Offer available to new subscribers who purchase an eligible device. $9.99/month after trial. Only one offer per Apple Account and only one offer per family if you’re part of a Family Sharing group, regardless of the number of devices you or your family purchase. This offer is not available if you or your family have previously subscribed to Apple Fitness+. Offer good for three months after eligible device activation. Plan automatically renews until cancelled. Restrictions and other terms apply.
Apple Fitness+ requires a subscription and compatible hardware and software. See here for compatibility details.
To get the newest features, make sure your devices are running the latest software version.</li>
            <li>2. Trade-in values will vary based on the condition, year, and configuration of your eligible trade‑in device. Not all devices are eligible for credit. You must be at least the age of majority to be eligible to trade in for credit or for an Apple Gift Card. Trade‑in value may be applied toward qualifying new device purchase, or added to an Apple Gift Card. Actual value awarded is based on receipt of a qualifying device matching the description provided when estimate was made. Sales tax may be assessed on full value of a new device purchase. In‑store trade‑in requires presentation of a valid photo ID (local law may require saving this information). Offer may not be available in all stores and may vary between in‑store and online trade‑in. Some stores may have additional requirements. Apple or its trade‑in partners reserve the right to refuse, cancel, or limit quantity of any trade‑in transaction for any reason. More details are available from Apple’s trade-in partner for trade‑in and recycling of eligible devices. Restrictions and limitations may apply.</li> <br/>
             <li>To access and use all Apple Card features and products available only to Apple Card users, you must add Apple Card to Wallet on an iPhone or iPad that supports and has the latest version of iOS or iPadOS. Apple Card is subject to credit approval, available only for qualifying applicants in the United States, and issued by Goldman Sachs Bank USA, Salt Lake City Branch.</li> <br/>
             <li>Apple Payments Services LLC, a subsidiary of Apple Inc., is a service provider of Goldman Sachs Bank USA for Apple Card and Savings accounts. Neither Apple Inc. nor Apple Payments Services LLC is a bank.</li> <br/>
             <li>If you reside in the U.S. territories, please call Goldman Sachs at 877-255-5923 with questions about Apple Card.</li> <br/>
             <li>Learn more about how Apple Card applications are evaluated at support.apple.com/kb/HT209218.</li> <br/>
             <li>A subscription is required for Apple Arcade, Apple Fitness+, Apple Music, and Apple TV.</li> <br/>
             <li>Features are subject to change. Some features, applications, and services may not be available in all regions or all languages.</li> <br/>
           </ul>
            <hr>
        </section>

        <div class="footer-links-grid">
            <div class="footer-col">
                <h3>Shop and Learn</h3>
                <ul>
                    <li><a href="#">Store</a></li>
                    <li><a href="#">Mac</a></li>
                    <li><a href="#">iPad</a></li>
                    <li><a href="#">iPhone</a></li>
                    <li><a href="#">Watch</a></li>
                    <li><a href="#">Vision</a></li>
                    <li><a href="#">AirPods</a></li>
                </ul>
                <h3>Apple Wallet</h3>
                <ul>
                    <li><a href="#">Wallet</a></li>
                    <li><a href="#">Apple Card</a></li>
                    <li><a href="#">Apple Pay</a></li>
                </ul>
            </div>

            <div class="footer-col">
                <h3>Account</h3>
                <ul>
                    <li><a href="#">Manage Your Apple Account</a></li>
                    <li><a href="#">Apple Store Account</a></li>
                    <li><a href="#">iCloud.com</a></li>
                </ul>
                <h3>Entertainment</h3>
                <ul>
                    <li><a href="#">Apple One</a></li>
                    <li><a href="#">Apple TV+</a></li>
                    <li><a href="#">Apple Music</a></li>
                </ul>
            </div>

            <div class="footer-col">
                <h3>Apple Store</h3>
                <ul>
                    <li><a href="#">Find a Store</a></li>
                    <li><a href="#">Genius Bar</a></li>
                    <li><a href="#">Today at Apple</a></li>
                    <li><a href="#">Apple Camp</a></li>
                </ul>
            </div>

            <div class="footer-col">
                <h3>For Business</h3>
                <ul>
                    <li><a href="#">Apple and Business</a></li>
                    <li><a href="#">Shop for Business</a></li>
                </ul>
                <h3>For Education</h3>
                <ul>
                    <li><a href="#">Apple and Education</a></li>
                </ul>
            </div>

            <div class="footer-col">
                <h3>Apple Values</h3>
                <ul>
                    <li><a href="#">Accessibility</a></li>
                    <li><a href="#">Education</a></li>
                    <li><a href="#">Environment</a></li>
                </ul>
                <h3>About Apple</h3>
                <ul>
                    <li><a href="#">Newsroom</a></li>
                    <li><a href="#">Investors</a></li>
                    <li><a href="#">Contact Apple</a></li>
                </ul>
            </div>
        </div>

        <section class="footer-bottom">
            <p>More ways to shop: <a href="#">Find an Apple Store</a> or <a href="#">other retailer</a> near you.</p>
            <hr>
            <div class="footer-legal">
                <p>Copyright © 2026 Apple Inc. All rights reserved.</p>
                <ul class="legal-links">
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Terms of Use</a></li>
                    <li><a href="#">Sales and Refunds</a></li>
                    <li><a href="#">Legal</a></li>
                    <li><a href="#">Site Map</a></li>
                </ul>
                <a href="#">United States</a>
            </div>
        </section>
    </div>
</footer>
            


</body>

</html>
