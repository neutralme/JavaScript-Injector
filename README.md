
# JavaScript Executor For Android
<h3>How to run?</h3>
1. Open browser in your android device.<br>
2. Click on search bar
<center><img src="a.jpg"></center>
3. Paste the code from below.<br>
<h4>Offline Version</h4>

```javascript
javascript: (function(){try{function createElem (elem) {return document.createElement(elem);}function setAtr (elem, atr, val) {(elem).setAttribute(atr, val);}function tell(data) {alert(data);}var background = createElem("section"),input = createElem("input"),button = createElem("button"),text = createElem("p");setAtr(background, "style", "margin: 10px; padding: 4px; border: 2px solid #FF0072; border-radius: 10px; width: 90%; height: 100px;  box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px, rgba(0, 0, 0, 0.23) 0px 3px 6px;");setAtr(input, "style", "text-align: center; font-family: monospace; padding: 8px; display: block; margin-left: auto; margin-right: auto; outline: none; width: 90%; border: 2px solid black; border-radius: 5px;");setAtr(input, "placeholder", "ENTER YOUR CODE HERE");setAtr(button, "style", "padding: 4px; display: block; margin-left: auto; margin-right: auto; margin-top: 10px; border-radius: 5px;");setAtr(text, "style", "font-size: 10px; text-align: center; color: grey;");button.innerHTML = "EXECUTE";text.innerHTML = "BY NEUTRAL ME";document.body.appendChild(background);document.body.getElementsByTagName("section")[0].appendChild(input);document.body.getElementsByTagName("section")[0].appendChild(button);document.body.getElementsByTagName("section")[0].appendChild(text);button.onclick = function() {if (input.value.length > 2) {try {eval(input.value);text.innerHTML = "Executed successfully!"} catch(e) {tell(e);}}}} catch(e){alert(e);}})();
```
<h4>Online version</h4>

```javascript
javascript: (function(){var script = document.createElement("script");script.src = "//yourjavascript.com/50022205201/script.js";document.body.appendChild(script);})();
```
4. There you go

<center><img src="b.jpg"></center>
• Created via: <a href="https://play.google.com/store/apps/details?id=io.spck">Spck Editor</a> (<span style="color: #00FF00;">Android</span>)<br>
• Icons made from: <a href="https://play.google.com/store/apps/details?id=xeus.iconic">Iconic</a> (Android)<br>
• Instagram: <a href="https://www.instagram.com/sharma0rohit/">sharma0rohit</a>
