# camera
!DOCTYPE html> &lt;html> &lt;head>     &lt;title>Purchase&lt;/title> &lt;link rel="stylesheet" type="text/css" href="camerashopstyle.css"> &lt;/head> &lt;body>      &lt;div class="header">   &lt;h1 style="color: white;">The Game&lt;/h1>   &lt;p style="color: white;">Welcome to the website where you can find second hand playstation games.&lt;/p> &lt;/div>  &lt;div class="topnav">   &lt;a href="index.html">Home&lt;/a>   &lt;a href="products.html">Products&lt;/a>   &lt;a href="purchase.html">Purchase&lt;/a>   &lt;a href="contact.html" style="float:right">Contact&lt;/a> &lt;/div>   &lt;table>   &lt;tr>     &lt;th>Cameras&lt;/th>     &lt;th>Number of Items&lt;/th>     &lt;th>Cost ($)&lt;/th>   &lt;/tr> &lt;tr>   &lt;td>                  &lt;input name="product" value="12.95" type="checkbox" id="p1" onclick="totalIt()"/>                 Candy $12.95               &lt;/td>             &lt;td>&lt;select name="quantity" id="quantity1" value="1" onchange="totalIt()">   &lt;option value="1" selected disabled=true>Units&lt;/option>   &lt;option value="1">1&lt;/option>   &lt;option value="2">2&lt;/option>   &lt;option value="3">3&lt;/option>   &lt;option value="4">4&lt;/option> &lt;/select> &lt;/td>                 &lt;td>                                &lt;input value="$0.00" readonly="readonly" type="text" id="total"/>            &lt;/td>    &lt;/tr> &lt;script src="shopcanon.js">&lt;/script>  &lt;/body> &lt;/html>   
