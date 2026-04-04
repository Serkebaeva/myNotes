- **HTML Basics**
  collapsed:: true
	- ```
	- <**!doctype html**>
	  
	  <**html lang="en"**>
	  
	      <**head**>
	  
	          <**title**>just a Website<**/title**>
	  
	          <**style**>
	  
	              **img** {
	  
	                  border: 1px solid # ccc;
	  
	                  padding: 5px;
	  
	                  width: 150px;
	  
	                  border-radius: 75px;
	  
	                  margin-top: 30px;
	  
	                  margin-bottom: 2px;
	  
	                  float: left;
	  
	                  margin-right: 20px; object-fit: cover;
	  
	              }
	  
	              .code_example {
	  
	                  font-weight: bold;
	  
	                  color: # 333;
	  
	              }
	  
	              .one {
	  
	                  font-size: 15px;
	  
	                  color: # 333;
	  
	              }
	  
	              .two {
	  
	                  font-size: 18px;
	  
	                  color: # 333;
	  
	              }
	  
	              .three {
	  
	                  font-size: 15px;
	  
	                  color: red;
	  
	              }
	  
	          </style>
	  
	      </head>
	  
	      <body>
	  
	          <p class="three">
	  
	              **!image elements can not have any children, so they are self-closing tags**
	  
	          </p>
	  
	          <p class="code_example">
	  
	              &lt;img src="images/download.jpg" alt="Jackie Chan smiling"&gt;
	  
	          </p>
	  
	          <!-- 
	  
	      The Escape Characters
	  
	      To make this work, you'll swap the brackets for these codes:
	  
	  **&lt; (less than) replaces <**
	  
	  **&gt; (greater than) replaces >**
	  
	      !!! Why use a **<pre>** or **<code>** tag?
	  
	  While putting it in a paragraph works, if you want it to look like actual code (usually with a monospaced font like Courier), it's a "best practice" to wrap it in <code> tags. If you have multiple lines, use <pre> to keep your spacing intact.
	  
	      -->
	  
	          <div>
	  
	              <img src="images/download.jpg" alt="Jeckie Chan smiling" height="200" />
	  
	              <p class="one">
	  
	                  ***border-radius: HALF of width is gonna make the image circular,** so in
	  
	                  this case, 75px from 150px
	  
	              </p>
	  
	          </div>
	  
	          <!-- one line
	  
	              & 
	  
	              multi line 
	  
	              comments in HTML
	  
	              -->
	  
	          <br />
	  
	          <p class="two">
	  
	              - The SRC attribute is used to specify the path to the image file
	  
	          </p>
	  
	          <p class="two">
	  
	              - the ALT attribute is used to provide alternative text for the image,
	  
	              which is displayed if the image cannot be loaded or if the user is using a
	  
	              screen reader
	  
	          </p>
	  
	      </body>
	  
	  </html>
	- ```
- **!** - in vs code with exclamation mark we can bring up **HTML structure** boilerplate. <!DOCTYPE html>
- some **[[TAGS]]**
  collapsed:: true
	- **<em>** - the em element represents stress emphasis of its contents.
	- **<strong>** - the element represents strong importance, seriousness, or urgency for its contents.
	- **&copy;** -> copyright symbol..
	- **&nbsp;** -> stands for **non-breaking space** in HTML. It creates a space between words or characters that prevents a browser from automatically breaking a line at that point. It is commonly used to keep items together (e.g., "$10" or "10 kg") to prevent the number from appearing on one line and the unit on the next.
- HTML [[entities]]
	- dev.w3.org
- **HTML** section [[URL]]
	- ``` /h2 id="section-css">CSS</h2>``` -> skip to CSS section
	- ```a href="# section-css">CSS</a>```
	- ```a href="# ">jump to top</a>``` -> GO TO TOP! of the page..
	- ```a href="https://google.com" target="_blank">Google</a>``` -> go to Google in a new tab..
	- ```a href="mailto:aiza@yahoo.com">email me</a>```
- [[entities]] [[Carriage returns]] and  [[thematic break line]]
	- **<br><br />**
	- ** [[<pre>]] **
	- [[<hr>]]