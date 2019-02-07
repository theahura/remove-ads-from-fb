FB allows you to see all of the advertisers who have added your contact information.  
You can purposely hide ads from all of them.  
  
Go to: https://www.facebook.com/ads/preferences/?entry_product=ad_settings_screen  
  
Hit f12 to open the developers console, and then hit Console.  
  
Drop this piece of code into the console:  

```javascript
try {
	while (true) {document.getElementsByClassName('_45yr')[0].click()}
} catch(err) {}

console.log('Number of advertisers:' + document.getElementsByClassName('_2b2n _2b2o').length)

for (i = 0; i < document.getElementsByClassName('_2b2n _2b2o').length; i++) { 
	try {
		console.log(i)
		document.getElementsByClassName('_2b2n _2b2o')[i].click()
	} catch (err) {}
}
```
Note that the variables '_45yr' and '_2b2n _2b2o' may change.  
To fix this, replace those classnames by right clicking on the element on the screen that you want to click,  
hit 'Inspect Element' (which should go to the elements tab of the dev console), and look for 'class=X'. 
