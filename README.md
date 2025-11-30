# Locators
With locators we are able to locate ui elemnts on webpage.


# 1. Locators
![UI Elements](image.png)
![Locators](image-1.png)
# 1.1 Different types of locator
![alt text](image-2.png)
~~~
Note: below locators are present inside html elemnt as attribute, to find these locators we have to inspect html code.

1. id = "Value"
eg. <button id="but2" type="button" contenteditable="true">Button2</button>

2. name = "Value"
eg. <button name="samename" type="button">Login</button>

3. class = "Value"
eg. <div class="widget HTML" data-version="1" id="HTML1">

4. Link text = "text between anchor tag"
eg. <a id="selenium143" href="http://www.Selenium143.blogspot.com" target="_blank">http://www.Selenium143.blogspot.com</a>

5. css selector = css selector value of ui elemnt

6. xpath = xpath value of ui element

7. Dom locator
eg. dom =document.getElementById("but1")
<button id="but1" type="button" disabled="">Button1</button>
~~~

# 1.2 priority of locators
![multi-locator-for-single-element](image-4.png)