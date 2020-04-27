<h1><strong>CSS</strong></h1>
<img src="https://www.tutorialrepublic.com/lib/images/css-illustration.png" height=350px width=1000px/>
<h2>Background</h2>
<p><em>background</em>: &nbsp; pink<br></p>
<p><em>background</em>: &nbsp;  url(image)<br></p>
<p><em>background-repeat</em>: &nbsp;  no-repeat <br></p>
<p><em>background-size</em>: &nbsp;  cover <br></p>
<br>
<br>



<h2>Border</h2>
<p><em>border</em>: &nbsp; 5px &nbsp; &nbsp; solid&nbsp; &nbsp;  purple<br></p>
<br>
<br>

<h2>Box Model</h2>
<p>Every element has a box around it</p>
<img src="https://miro.medium.com/max/2948/1*gq1B7v2_gDEi3jkAwAvZNQ.png" height="150" width="200">
<ul>
  <li><strong>Element</strong> - <em>width/height:</em>&nbsp;&nbsp;200px&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;can also use % of the parent element </li>
  <li><strong>Padding</strong> - <em>padding:</em>&nbsp;&nbsp;10px&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sets 10px of padding all around</li>
  <li><strong>Margin</strong> - <em>margin:</em>&nbsp;&nbsp;10px&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sets 10px of margin all around, we can also do 0 auto which will set top and bottom to 0 and left and right to auto(center)</li>
  <li><strong>Border</strong> - <em>border:</em>&nbsp;&nbsp;2px solid blue</li>
</ul>
<br>
<br>

<h2>CSS COLORS</h2>
<h4>Hex</h4>
<p>
  <em>color</em>:&nbsp;  #RRGGBB
</p>
<h4>RGB</h4>
<p>
  <em>color</em>:&nbsp;  rgb(0,255,0)
</p>
<h4>RGBA (A is transparency)</h4>
<p>
  <em>color</em>: &nbsp; rgb(0,255,0, .5)
</p>
<strong>CSS Colours</strong> - https://colours.neilorangepeel.com/
<br>
<br>
<br>
<br>



<h2>Float</h2>
<p>Takes the elements out of the normal flow. For instance, we have 2 divs which are block elements, float would overwrite this.</p>
<p><em>float</em>: &nbsp; left &nbsp;&nbsp;&nbsp;the div's orientation/flow would be changed to  floating always to the left</p>
 <br>
<br>
<br>
<br>

<h2>Fonts and Texts</h2>
<ul>
  <li><em>font-family:</em> "Arial"</li>
  <li><em>font-size:</em> 200px </li>
  <ul>
    <li>em - control the size base on the parent element. For instance, we have a p and we set one sentence in it to 2 em, the sentence will be doubled the size of p. Another example would be setting an h2 to 5 em, it will be 5 times bigger than the body since this is its parent element.<li/>
    </ul>
  <li><em>font-weight:</em>&nbsp;&nbsp;bold&nbsp;&nbsp;&nbsp;&nbsp;(100-800)</li>
  <li><em>line-height:&nbsp;&nbsp;</em>2&nbsp;&nbsp;&nbsp;&nbsp;double-spaced</li>
  <li><em>text-align:&nbsp;&nbsp;</em>center</li>
  <li><em>text-decoration:&nbsp;&nbsp;</em>underline</li>
  <li><em>text-transform:&nbsp;&nbsp;</em>uppercase</li>
  </ul>
<strong>Available fonts in CSS</strong> -&nbsp;&nbsp;https://www.cssfontstack.com/
 <br>
<strong>Google Fonts</strong> -&nbsp;&nbsp; https://fonts.google.com/
<br>
<br>
<br>
<br>




<h2>Selectors</h2>
<ul>
  <li><strong>Element/Type</strong></li>
  <li><strong>Class</strong>&nbsp;&nbsp;&nbsp;&nbsp; <em>.class</em></li>
  <li><strong>ID</strong>&nbsp;&nbsp;&nbsp;&nbsp; <em>#id</em></li>
  <li><strong>Descendant</strong>&nbsp;&nbsp; <em>li a</em> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; selects every a in an li</li>
  <li><strong>Adjacent</strong>&nbsp;&nbsp; <em>h4 + li</em> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; selects all li that comes after h4</li>
  <li><strong>Nth of Type</strong>&nbsp;&nbsp; <em>ul:nth-of-type(3)</em> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; selects third ul</li>
</ul>
<br>
<br>



<h2>Specificity</h2>
<p>An element can be targeted by multiple styles/selectors. The style that is closest/most specific to the element will be applied by CSS. 
  <br>
  ID > Class > Element/Type</p>


