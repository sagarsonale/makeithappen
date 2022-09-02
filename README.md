<!DOCTYPE html> 
<html>
<head>
<title>BlockChain in HelthCare</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
html,body,h2,h3,h4 {font-family:"Lato", sans-serif, color:white;}
h1,p,li {color:white;,font-family:"Lato", sans-serif}
pre {border: 1.75px solid white;
  border-radius: 8px;
  padding: 5px;}
.mySlides {display:none}
.w3-tag, .fa {cursor:pointer}
.w3-tag {height:15px;width:15px;padding:0;margin-top:2px}
img {width: 100%;
}
</style>
</head>

<body style="background-color:#008089">

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-large w3-light-grey">
    <div class="w3-col s3">
      <a href="#intro" class="w3-button w3-block">Introduction</a>
    </div>
    <div class="w3-col s3">
      <a href="#prostmt" class="w3-button w3-block">Problem Statement</a>
    </div>
    <div class="w3-col s3">
      <a href="#prosoln" class="w3-button w3-block">Solution to the problem</a>
    </div>
    <div class="w3-col s3">
      <a href="#tops" class="w3-button w3-block">Topics covered on this track</a>
    </div>
  </div>
</div>

<!-- Content -->
<div class="w3-content" style="max-width:1100px;margin-top:80px;margin-bottom:80px">


  <div class="w3-panel w3-center">

<pre>
    <h1><b>Health Management Using BlockChain</b></h1>
    <p style="color:white">hashing always, for you and your better health</p>
	</pre>
  </div>

  <!-- Slideshow -->
  <div class="w3-container">
    <div class="w3-display-container mySlides">
      <img src="imgs\img1.jpeg" style="width:100%">
      <div class="w3-display-topleft w3-container w3-padding-32">
        <span class="w3-white w3-padding-large w3-animate-bottom">hashing always, for you and your better health</span>
      </div>
    </div>
    <div class="w3-display-container mySlides">
      <img src="imgs\img3.jpeg" style="width:100%">
      <div class="w3-display-middle w3-container w3-padding-32">
      </div>
    </div>
    <div class="w3-display-container mySlides">
      <img src="imgs\img2.jpeg" style="width:100%">
      <div class="w3-display-topright w3-container w3-padding-32">
      </div>
    </div>

    <!-- Slideshow next/previous buttons -->
    <div class="w3-container w3-dark-grey w3-padding w3-xlarge">
      <div class="w3-left" onclick="plusDivs(-1)"><i class="fa fa-arrow-circle-left w3-hover-text-teal"></i></div>
      <div class="w3-right" onclick="plusDivs(1)"><i class="fa fa-arrow-circle-right w3-hover-text-teal"></i></div>
    
      <div class="w3-center">
        <span class="w3-tag demodots w3-border w3-transparent w3-hover-white" onclick="currentDiv(1)"></span>
        <span class="w3-tag demodots w3-border w3-transparent w3-hover-white" onclick="currentDiv(2)"></span>
        <span class="w3-tag demodots w3-border w3-transparent w3-hover-white" onclick="currentDiv(3)"></span>
      </div>
    </div>
  </div>
<p>-----------------------------------------------------------------------------------------------------------------------------------------------------------
  <!-- Grid -->
  <div class="w3-row w3-container" id="intro">
    <div class="w3-center w3-padding-64">
      <span class="w3-xlarge w3-bottombar w3-border-dark-grey w3-padding-16 ">Introduction</span>
    </div>
    <div class="w3-center">
<p>Human Healthcare has evolved from the ancient period of time from natural medical procedures like
<b>Ayurveda</b> to today's modern medical procedures like <b>Allopathic medical science</b> where performing
complex surgeries and finding cure to so called <b>incurable/terminal</b> diseases like cancer, etc.. has
become easy by using Artificial Intelligence and ever-evolving computer technology. Although human
race has uncovered many possibilities in the healthcare sector, yet there is one specific field where
need to put on extra focus and work upon and that is to create a Patient Health Data storage and
management system which would provide a hassle free experience for the patients to store all of their
medical reports and statics - from their Birth certificate to live health status monitoring using IoT and
storing this data in uniformed manner so that is easily accessed by both patient and the doctors .</p>
</div>
    <div class="w3-col l3 m6 w3-light-grey w3-container w3-padding-16">
      <h3>Design</h3>
      <p>Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.</p>
    </div>

    <div class="w3-col l3 m6 w3-grey w3-container w3-padding-16">
      <h3>Branding</h3>
      <p>Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.</p>
    </div>

    <div class="w3-col l3 m6 w3-dark-grey w3-container w3-padding-16">
      <h3>Consultation</h3>
      <p>Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.</p>
    </div>

    <div class="w3-col l3 m6 w3-black w3-container w3-padding-16">
      <h3>Promises</h3>
      <p>Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.</p>
    </div>
  </div>

<p>-----------------------------------------------------------------------------------------------------------------------------------------------------------
  <div class="w3-row-padding" id="prostmt">
    
  <div class="w3-center w3-padding-64">
      <span class="w3-xlarge w3-bottombar w3-border-dark-grey w3-padding-16 ">Problem Statement</span>
    </div>
    <div>
<p><li>lack of specific Database to store all the details of patients medical reports, medication history and
many medical related parameters which are protected against Hacks and data breaches.</li>
<li>When a patient is bought to the hospital in unconscious state or in a condition where they might not
remember their previous medical records, and the patient may be allergic to certain medications
and doctors would require right data to perform medical action on the patient. Due to lack of this
data, the Doctor may perform ineffective medical procedure on the patient and that might not come
with higher success rate. But if we have a database which houses the patients medical records
then the Doctor can provide the patient with the right cure.</li>
<li>lack of security on the patients private health data stored since it is centralised and stored on one
or few servers which is prone to cyber hacks and data breaches.</li></p>
</div>
  </div>
<p>-----------------------------------------------------------------------------------------------------------------------------------------------------------
<div class="w3-row-padding" id="prosoln">
    
  <div class="w3-center w3-padding-64">
      <span class="w3-xlarge w3-bottombar w3-border-dark-grey w3-padding-16 ">Solution to the problem</span>
    </div>
    <div>
<p>To build a De-centralised data storage system which stores the patient health records which contain -
prescription, health analytics, patients performance, medication and treatment history in an encrypted
manner in a distributed computer systems which is immune against hacks and data breaches.
Here the users are the sole owners of their data and can provide permission to various individuals
(doctors) or groups (hospitals) to access and study the data under the user supervision. Here the Data
is completely in the users control and no single entity controls the data and since it is immutable it
cannot be altered once fed into to block-chain so that the authenticity and originality of the data in
blocks is maintained. By integrating the existing technology with block-chain we can ensure security,
scalability, and accessibility of the traditional system and open multiple doors for the betterment of this
industry.
</p>
</div>
  </div>
<p>-----------------------------------------------------------------------------------------------------------------------------------------------------------

  <!-- Grid -->
  <div class="w3-row-padding" id="tops">
    <div class="w3-center w3-padding-64">
      <span class="w3-xlarge w3-bottombar w3-border-dark-grey w3-padding-16">Topics covered on this track</span>
    </div>
<div>
<ol>
	<h2><li>Executive summary</h2></li>
	<ul>
		<h3><li>Mission </h3>
		<p>To Build a decentralised and secure platform to store the personal heath information of patients
on a private Blockchain ledger which facilitates :-</p>
		<ul>
			<li>Easy storing, sharing and processing of data.</li>
<li>where users have complete control on their data (user can control inflow and outflow of their
personal data)</li>
<li>An efficient System which is immune to hacks, data breach, and mutation.</li>
<li>easy UI/UX and accessible by the user and can even be operated with individuals with minimal
knowledge\education.</li>
</ul>
<h3><li>Company objective</li></h3>
<p><b>To build a completely free service that would help billions of individuals to get the right medical
treatment utilising our service, improvise the medical care sector and help make this world a
better place.
</b></p>
<p>by utilising the current blockchain network we want our company to be market leader in terms of
providing free yet quality data storage service to the people around the globe. We want this service to
cater every single individual of this planet irrespective of their citizenship, race, gender, etc and help
them get better in terms of personal health.<p>
<h3><li>Growth Highlights</li></h3>
<p>over the past 6-7 years we have seen how the number of people getting access to the Internet boomed
because of the JIO revolution and we expect the blockchain technology to boom in the upcoming years
and want to make sure that we would be making complete use of this technological advancement and
withing 10 years from now we expect our service to be catering over a billion users worldwide and our
aim is to make our service available to ever single human on this planet.
</p>
<h3><li>Products we will be offering</li></h3>		
<ol>
<li>Health data storage
<li>live health monitoring using IoT devices like wearable.
<li>Disease detection using AI and ML
<li>hassle free transfer of data within blockchain
<li>Medication/drugs suggestion
<li>and many services related to healthcare
</ol>
</ul>
<h2><li>Need analysis</li></h2>
<p>In healthcare, a blockchain network is useful to preserve and exchange patients data. Blockchain
application can accurately identify serious illness and even dangerous ones in patients by processing
and studying their data.<p>
<p>with that Blockchain also plays a decisive part in handling deception in clinical trials for better
healthcare outcomes and the lack of platform to maintain a patients records triggered the idea to create
this service where in the user just has to register once in their entire life time where they get to store
and manage all of their data dealing with their personal health can be stored safely by encryption and
they can also provide the data to their doctor during their checkup so that the doctors examining them
can get a detailed history of their health and their performance so that they can provide the patients
with the right and effective cure and hence eliminate the usage of physical documents and easy
analysis of data.
</p>
<h2><li>Scope of the idea</li></h2>
<p>
Blockchain and Artificial Intelligence technology can be combined to improve the quality of care in
healthcare systems. It will cut costs in the medical industry, and as a result, healthcare will become
more accessible and affordable. Blockchain enables encrypted data, which AI requires</p>
<h2><li>Step wise implementation of the plan</li></h2>
<p><b>The following are the steps our company is planning to take in order to achieve our goals</b></p>
<ol>
<li>
 Raise awareness on our service, blockchain and its application
<li>Promote our service and Build user base
<li>Implement the Artificial Intelligence and Machine learning
<li>Discover medicines and drugs by studying user data using AI/ML
</ol>
<h2><li>Impact of the idea</li></h2>
<p>The latter half of the 20th century and the initial years of 21st centuries have seen some massive inventions and discoveries that changed our world forever. Be it the computer, the internet, and now the new sensation Blockchain.
Don’t be surprised If I put Blockchain with internet as many experts firmly believe blockchain to be most significant invention since the internet. Some also call it the new or “next internet”.
</p>
<p>Blockchain has emerged as a new buzzword in the tech world. The rise of Bitcoin and other cryptocurrencies have certainly helped blockchain to get the spotlight.
</p>
<p>However, the experts believe that Blockchain is not a fad as it’s not all about the cryptocurrencies, it promises to be a lot more than that.
Impactness
</p>
<h2><li>Timeline for execution</li></h2>
<h2><li>References</li></h2>
<p>Block chain is a decentralised list of digital records linked together by cryptography. Each record is
known as a ‘block’. Every block contains a cryptographic hash of the previous block i.e., a mathematical
algorithm, a timestamp, and data of that transaction.
</p>
<ul>
<li>single/permanent strong password system.
<li>The execution of the idea starts with building a platform (Application/web page) that would facilitate
the users interaction with the ongoing/running block chain and this platform would also facilitate the
input and output of the data into and out of the ledger.
<li>when ever the user signs up with the service he is welcomed with a permanent 12-24 word
password called Seed phrase this is a permanent password and it cannot be changed later and
by loosing this key the user loosed access to their data
seed phrase example - sun cap river edge conclude bottle man phone carrot seat key
root
these keys helps decrypt the user data
<li>Whenever the user initiates the transaction (pushes/requests data) on the
<ul>









</div>
<div class="w3-center">
<a href="#" class="w3-button w3-black w3-margin"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
</div>
<p>---------------------------------------------------------------------------------------------------------------------------------------------------------
<footer>
<div>
<p>Team - SSIT</p>
<p>participants - Ameer Salam, Vedashree H S, Balaji P S, Sagar Sonale T V
</p>
<div>
</footer>

<script>
// Slideshow
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function currentDiv(n) {
  showDivs(slideIndex = n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demodots");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length} ;
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" w3-white", "");
  }
  x[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " w3-white";
}
</script>

</body>
</html>
