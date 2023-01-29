# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
CSS:

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:white;
  color: #1ab7f5;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 450px;
  text-align: center;
  font-family:'fantasy';
  font-size: 70px;
  background-image: url("https://www.incimages.com/uploaded_files/image/1920x1080/getty_913588226_414027.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #1a0101;
}

.menu {
  display: block;
  width: 100%;
  height: 80px;
  font-size: 25px;
  background-color: whitesmoke;
  text-align: right;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: rgb(2, 1, 1);
}

.content {
  display: block;
  width: 100%;
  background-color: whitesmoke;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
  margin-top: 50px;
}

.contenttext {
  margin-bottom: 50px;
  text-align: justify;
  font-size: 20px;
  color: #1a0101;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}
.productitem .peopleimg{
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50px;
  margin-bottom: 5px;
}
.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #a644f7;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #66060b;
}

Home Page Coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>GLOBAL BRIDGEO</title>
    <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/imgic.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="menu">
        <img src="./img/imgic.jpg" alt="imgic" width="50" height="50" style="float: left;">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      
      </div>
      <div class="banner">GLOBAL WORK PLATFORM</div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/imgw.png" alt="img">
          <div class="contenttext">
            A global network is any communication network which spans the entire Earth. 
            Ecosystems and connectivity also create an efficient environment for electronic
            trading, algorithmic execution, direct market access and enhancing market data.
            The ability to sell short as well as borrowing and lending securities is heavily 
            dependent on a connected market.
            <br>
            
            Global BridgeO helps you to the next level of connectivity thorough the world.
            It plays as the part of a bridge to connect the world for business and social development
            <ul>        
            <li>BENEFITS:</li>
            <li>Creating new jobs.</li>
            <li>Overcoming poverty.</li>
            <li>Revolutionizing third world healthcare.</li>
            <li>Boosting aid relief after natural disasters.</li>
            <li>Making construction more productive.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 GLOBAL BRIDGEO, Developed by Dharshini DS.
      </div>
    </div>
  </body>
</html>

Product Page Coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>GLOBAL BRIDGEO</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/imgic.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="menu">
        <img src="./img/imgic.jpg" alt="img" width="50" height="50" style="float: left;">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="banner">GLOBAL WORK PLATFORM</div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/book1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Technology Meets Efficiency</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/book2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Platforms for Wireless Communication</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                 <div class="itemimage">
                 <img src="./img/book3.jpg"  alt="product image">
                 </div>
                 <div class="itemname">Global Internet Connectivity</div>
                 <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                 <div class="itemimage">
                 <img src="./img/book4.jpg"  alt="product image">
                 </div>
                 <div class="itemname">Networks in the Global World</div>
                 <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                 <div class="itemimage">
                 <img src="./img/book5.jpg"  alt="product image">
                 </div>
                 <div class="itemname">Fundamentals of Communication System</div>
                 <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                 <div class="itemimage">
                 <img src="./img/book6.jpg"  alt="product image">
                 </div>
                 <div class="itemname">Global Networks</div>
                 <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                 <div class="itemimage">
                 <img src="./img/book7.jpg"  alt="product image">
                 </div>
                 <div class="itemname">Trends in Networking and Communication</div>
                 <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                 <div class="itemimage">
                 <img src="./img/book8.jpg"  alt="product image">
                 </div>
                 <div class="itemname">Security and Privacy</div>
                 <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="./img/book9.jpg"  alt="product image">
                </div>
                <div class="itemname">International Economics</div>
                <div class="itemprice">Price: Rs.10,000.00 </div>
             </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="./img/book10.jpg"  alt="product image">
                </div>
                <div class="itemname">Encyclopedia</div>
                <div class="itemprice">Price: Rs.10,000.00 </div>
             </div>
             <div class="productitem"> 
                <div class="itemimage">
              <img src="./img/book11.jpg"  alt="product image">
              </div>
              <div class="itemname">Computer Networks</div>
              <div class="itemprice">Price: Rs.10,000.00 </div>
             </div>
             <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/book12.jpg"  alt="product image">
              </div>
              <div class="itemname">Computer Networking</div>
              <div class="itemprice">Price: Rs.10,000.00 </div>
            </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 GLOBAL BRIDGEO, Developed by Dharshini DS.
      </div>
  </body>
</html>

People Page Coding:
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>GLOBAL BRIDGEO</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/imgic.jpg" type="image/x-icon" />
  </head>

   <body>
        <div class="container">
         <div class="menu">
          <img src="./img/imgic.jpg" alt="img"  width="50" height="50" style="float: left;">
          <div class="menuitem"><a href="/static/home.html">Home</a></div>
          <div class="menuitem"><a href="/static/products.html">Products</a></div>
          <div class="menuitemselected"><a href="/static/people.html">People</a></div>
          <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
        </div>
        <div class="banner">GLOBAL WORK PLATFORM</div>
        <div class="content">
          <div class="productcontent">
            
            <div class="productitems">
            <div class="productitem">
            <div class="peopleimg">
            <img src="./img/people1.jpg"  alt="peopleimg">
            </div>
            <div class="itemname">Sundhar Pichai</div>
            <div class="itemprice">CEO of Google</div>
        </div>
        <div class="productitem">
            <div class="peopleimg">
            <img src="./img/people2.jpg"  alt="peopleimg">
            </div>
            <div class="itemname">Satya Nadella</div>
            <div class="itemprice">CEO of Microsoft</div>
        </div>
        <div class="productitem">
           <div class="peopleimg">
           <img src="./img/people3.jpg"  alt="peopleimg">
           </div>
           <div class="itemname">Jeff Bezos</div>
           <div class="itemprice">CEO of Amazon</div>
        </div>
        <div class="productitem">
          <div class="peopleimg">
          <img src="./img/people4.jpg"  alt="peopleimg">
          </div>
          <div class="itemname">Vivek Paul Gundotra</div>
          <div class="itemprice">Vice President of Google</div>
        </div>
        <div class="productitem">
          <div class="peopleimg">
          <img src="./img/people5.jpg"  alt="peopleimg">
          </div>
          <div class="itemname">Rajiv Kumar </div>
          <div class="itemprice">Managing Director and Corporate Vice President of Microsoft</div>
        </div>
        <div class="productitem">
          <div class="peopleimg">
          <img src="./img/people6.jpg"  alt="peopleimg">
          </div>
          <div class="itemname">Salil Parekh</div>
          <div class="itemprice">CEO of Infosys</div>
        </div>
        </div>
      </div>
      </div>
          <div class="footer">
             Copyright &#169; 2021 GLOBAL BRIDGEO, Developed by Dharshini DS.
          </div>
       </div>
    </body>
</html>

Contact Us Page Coding:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>GLOBAL BRIDGEO</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/imgic.jpg" type="image/x-icon" />
  </head>

   <body>
      <div class="container">
      <div class="menu">
         <img src="./img/imgic.jpg" alt="imgic" width="50" height="50" style="float: left;">
         <div class="menuitem"><a href="/static/home.html">Home</a></div>
         <div class="menuitem"><a href="/static/products.html">Products</a></div>
         <div class="menuitem"><a href="/static/people.html">People</a></div>
         <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="banner">GLOBAL WORK PLATFORM</div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1>
          <div class="contenttext">
            ADDRESS: Global BridgeO, Internet city, Web world
            <br>
            Phone number: 6785456709
            <br>
            Email: bridgeo554@gmail.com
          </div>
        </div>
      </div>


          <div class="footer">
              Copyright &#169; 2021 GLOBAL BRIDGEO, Developed by Dharshini DS.
          </div>
        </div>
    </body>
</html>
```
## OUTPUT:
![output](/name1.png)
![output](/name2.png)
![output](/name3.png)
![output](/name4.png)
![output](/name5.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
