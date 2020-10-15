# ARrow-sandbox
Prove per js coding

Ciao, sto cercando di capire come utilizzare
GIThub per inserire codice javascript

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Arrays</h2>

<p>The best way to loop through an array is using a standard for loop:</p>

<p id="demo"></p>

<script>
var text, fLen, i;
fruits = new Array("Bananina", "Orange", "Apple", "Mango");
fLen = fruits.length;

text = "<ul>";
for (i = 0; i < fLen; i++) {
  text += "<li>" + fruits[i] + "</li>";
}
text += "</ul>";

document.getElementById("demo").innerHTML = text;

</script>

</body>
</html>
