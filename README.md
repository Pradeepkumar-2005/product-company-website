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
### Home.html :
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Pradeep Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Pradeep Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="products.html">Products</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Pradeep Private Limited, Developed by Pradeep Kumar.
      </div>
    </div>
  </body>
</html>
```
### products.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Pradeep Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Pradeep Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tally_bronze.png"  alt="product image">
                </div>
                <div class="itemname">Tally Bronze</div>
                <div class="itemprice">Price: Rs.5,000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/tally_scoreboard.png"  alt="product image">
              </div>
              <div class="itemname">Tally Scoreboard</div>
              <div class="itemprice">Price: Rs.50,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/tally-barcode.png"  alt="product image">
            </div>
            <div class="itemname">Tally Barcode Scanner</div>
            <div class="itemprice">Price: Rs.2,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/tally_datahub.png"  alt="product image">
          </div>
          <div class="itemname">Tally Data Transfer Hub</div>
          <div class="itemprice">Price: Rs.30,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/tally_printer.png"  alt="product image">
          </div>
          <div class="itemname">Tally Receipt printer </div>
          <div class="itemprice">Price: Rs.10,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/tally_inventory.png"  alt="product image">
          </div>
          <div class="itemname">Tally RFID Inventory system </div>
          <div class="itemprice">Price: Rs.1,00,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/tally_fitness.png"  alt="product image">
          </div>
          <div class="itemname">Tally Fitness Tracker </div>
          <div class="itemprice">Price: Rs.3,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/tally_buisness.png"  alt="product image">
          </div>
          <div class="itemname">Tally Buisness Management Suite </div>
          <div class="itemprice">Price: Rs.30,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/tally_navigator.png"  alt="product image">
          </div>
          <div class="itemname">Tally Navigator </div>
          <div class="itemprice">Price: Rs.7,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/tally_auto.png"  alt="product image">
          </div>
          <div class="itemname">Tally Automation Hub </div>
          <div class="itemprice">Price: Rs.3,00,000.00 </div>
        </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Pradeep Private Limited, Developed by Pradeep Kumar.
      </div>
    </div>
  </body>
</html>
```
### people.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Pradeep Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">Pradeep Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our People</h1>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/ceo.png" alt="product image">
                </div>
                <div class="itemname">Aravind</div>
                <div class="itemprice">Chief Executive Officer</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/CTO.png" alt="product image">
                </div>
                <div class="itemname">Karthik</div>
                <div class="itemprice">Chief Technology Officer</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/marketing-director.png" alt="product image">
                </div>
                <div class="itemname">Meera Srinivasan</div>
                <div class="itemprice">Marketing Director</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/design_lead.png" alt="product image">
                </div>
                <div class="itemname">Rajesh Menon</div>
                <div class="itemprice">Design Lead</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/developer.png" alt="product image">
                </div>
                <div class="itemname">Venkatesh</div>
                <div class="itemprice">Lead Developer</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/HR.png" alt="product image">
                </div>
                <div class="itemname">Deepa Krishnan</div>
                <div class="itemprice">Human Resource Manager</div>
            </div>
         
      <div class="footer">
        Copyright &#169; 2021 Pradeep Private Limited, Developed by Pradeep Kumar.
      </div>
    </div>
  </body>
</html>
```
### Contact.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Pradeep Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Pradeep Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitemselected"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Contact Us</h1>
          <p>Whatsapp - 123456789</p>
          <p>Intsagram - tally_jabsoft</p>
          <p>Gmail - jabez_s@gmail.com</p>
          <p>Address - v.o.c street, kasthuri bai nagar, west tambaram</p>
 
      <div class="footer">
        Copyright &#169; 2021 Pradeep Private Limited, Developed by Pradeep Kumar.
      </div>
    </div>
  </body>
</html>
```
### OUTPUT:
## Home Page:


## Product Page:


## People Page :

## Contact Page :


### Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
