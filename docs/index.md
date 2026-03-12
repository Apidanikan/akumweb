# AkuManusiaaWeb

Selamat datang di website ini! Website ini hanya berisi percobaan.

![Julius Caesar](https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Retrato_de_Julio_C%C3%A9sar_%2826724093101%29_%28cropped%29.jpg/250px-Retrato_de_Julio_C%C3%A9sar_%2826724093101%29_%28cropped%29.jpg)  

`Lorem ipsum dolor sit amet.`

<div markdown="0">
<form>
<input id="hexValue" placeholder="Hex value" style="padding: 1em;margin: 0.5em;border-radius: 0.4rem; border: solid 1px rgb(38, 38, 38); outline: none;color: blue;"/>
<input id="result" placeholder="Result" readonly  style="padding: 1em;margin: 0.5em;border-radius: 0.4rem; border: solid 1px rgb(38, 38, 38); outline: none;color: blue;"/>
<a onclick="document.getElementById('result').value = String.fromCodePoint(parseInt(document.getElementById('hexValue').value, 16))" style="text-decoration: none; color: white; background: rgb(91, 33, 182); padding: 0.5em; border-radius: 0.4em; cursor: pointer;">Convert</a>
</form>
</div>