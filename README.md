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
CSS Layout
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/grp.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
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
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
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
}

.contenttext {
  text-align: justify;
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
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```
home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Asin Cosmetics PVT LTD</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/grp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Asin Cosmetics PVT LTD</div>
     <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/grp.png" alt="tech">
          <div class="contenttext">
           <p> our Fancy items and Cosmetics online for Women from Asin Cosmetics PVT LTD
                         | Buy cosmetics in Whole sale| 7 Days Returns | Trend setting models | And much more</p>


            <ul>
              <li>Branded Products</li>
              <li>COD Available</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Asin Cosmetics PVT LTD, Developed by Asin Vardhini
      </div>
    </div>
  </body>
</html>
```
people.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Asin Cosmetics PVT LTD</title>
    <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/icon.png" type="image/x-icon"/>
  </head>

  <body>
    <div class="container">
      <div class="banner">Asin Cosmetics PVT LTD</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">   
          <h1>CEO of the Brand</h1>
          <div class="productitems">
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Delphine Arnault</div>
                  <div class="itemprice">President & CEO of Dior</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Selena Gomez</div>
                  <div class="itemprice">Founder & CEO of Rare Beauty</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Leena Nair</div>
                  <div class="itemprice">CEO of Chanel</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/4.png" alt="product image">
                  </div>
                  <div class="itemname">Tim Cook</div>
                  <div class="itemprice">CEO of MAC Cosmetics</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Huda Kattan</div>
                  <div class="itemprice">Founder & CEO of HUDA Beauty</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/7.jpg" alt="product image">
                  </div>
                  <div class="itemname">Michael Burke</div>
                  <div class="itemprice">CEO of louis vuitton</div>
              </div>

          </div>
          </div>       
      </div>
      <div class="footer">
        Copyright &#169; 2023 Asin Cosmetics PVT LTD, Developed by Asin Vardhini
      </div>
    </div>
  </body>
</html>
```
product.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Asin Cosmetics PVT LTD</title>
     <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/6.jpg" type="image/x-icon">

  </head>

  <body>
    <div class="container">
      <div class="banner"> Asin Cosmetics PVT LTD</div>
      <div class="menu">
     <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">   
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Dior Foundation</div>
                  <div class="itemprice">Price: Rs.2250 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">MAC Mascara</div>
                  <div class="itemprice">Price: Rs.1650 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Chanel Highlighter</div>
                  <div class="itemprice">Price: Rs.2450 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p4.jpg" alt="product image">
                  </div>
                  <div class="itemname">louis vuitton lipstick</div>
                  <div class="itemprice">Price: Rs.3290 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Rare Beauty Blush</div>
                  <div class="itemprice">Price: Rs.1450 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p6.jpg" alt="product image">
                  </div>
                  <div class="itemname">HUDA Beauty eyeshadow palette</div>
                  <div class="itemprice">Price: Rs.5450 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p7.jpg" alt="product image">
                  </div>
                  <div class="itemname">Rare Beauty lipstick</div>
                  <div class="itemprice">Price: Rs.1300 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p8.jpg" alt="product image">
                  </div>
                  <div class="itemname">HUDA Beauty lipstick</div>
                  <div class="itemprice">Price: Rs.2350 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p9.jpg" alt="product image">
                  </div>
                  <div class="itemname">Dior eyeshadow</div>
                  <div class="itemprice">Price: Rs.3280 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p10.jpg" alt="product image">
                  </div>
                  <div class="itemname">Chanel Lip Gloss</div>
                  <div class="itemprice">Price: Rs.1400 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p11.jpg" alt="product image">
                  </div>
                  <div class="itemname">MAC lip liner</div>
                  <div class="itemprice">Price: Rs.1250 </div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/p12.jpg" alt="product image">
                  </div>
                  <div class="itemname">Rare Beauty eyeshadow</div>
                  <div class="itemprice">Price: Rs.2370 </div>
              </div>
          </div>
          </div>       
      </div>
      <div class="footer">
        Copyright &#169; 2023 Asin Cosmetics PVT LTD, Developed by Asin Vardhini
      </div>
    </div>
  </body>
</html>
```
contactus.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Asin Cosmetics PVT LTD</title>
   <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/6.jpg" type="image/x-icon">
     
  </head>

  <body>
    <div class="container">
      <div class="banner">Asin Cosmetics PVT LTD</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          
            <h1>Contact Us</h1>
  <p>If you have any questions or feedback, please don't hesitate to reach out to us.</p>
  <ul>
    <li>Address: 321 , East Main Road Street, Tamilnadu , India</li>
    <li>Phone: +91 85746922431</li>
    <li>Email: contact@asincosmetic.com</li></ul>
  
<h2> Sales Inquiries</h2>

<ul><li>India 1800 103 11231800 572 3535</li></ul>
    <h2>Press Inquiries</h2> 
<ul><li>press@asincosmetic.com</li>

<li>Anu</li>
<li>anu@invensys.com</li></ul>
    <h2>Analyst Relations</h2> 

    <ul><li>Shraddha</li>
    <li>+1-925-924-9500</li>
    <li>shraddha@invensys.com</li></ul>
        <h2>Customer Relations</h2> 

    <ul><li>Sidharth</li>
    <li>Director of Sales & Customer Service</li>
    <li>sidharth@invensys.com</li>
    </ul>
    
  </div>
   <div class="footer">
        Copyright &#169; 2023 Asin Cosmetics PVT LTD, Developed by Asin Vardhini
      </div>
      </div>
</body>
</html>
```
## OUTPUT:

![Screenshot 2023-05-19 111130](https://github.com/AsinVardhini/productcompanywebsite/assets/119417735/4481aa15-9acf-4e6b-9f05-16cc9f29078c)

![Screenshot 2023-05-19 200025](https://github.com/AsinVardhini/productcompanywebsite/assets/119417735/c02d5c44-b145-4c57-9912-dc0fd2a34a6b)

![Screenshot 2023-05-19 200216](https://github.com/AsinVardhini/productcompanywebsite/assets/119417735/b4d28b59-a24d-476a-a2b3-ff41d034cdaa)


### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
