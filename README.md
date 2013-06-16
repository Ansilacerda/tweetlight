[Tweetlight](http://www.pinceladasdaweb.com.br/blog/uploads/tweetlight/)
==========

Display your latest tweets with pure JavaScript and PHP OAuth Library.

##Usage
1. Add the code below to your HTML, where the latest tweets should appear:
```html
<ul id="tweets"></ul>
```

2. Paste right before your page's closing `</body>` tag:
```console
<script type="text/javascript" src="src/tweetlight.js"></script>
```

3. From within a script tag or a JS file
```javascript	
	Tweetlight.init({
		username: 'pinceladasdaweb',	// Twitter username
		count: 4						// Number of tweets to display
	});
```

4. In the tweets.php file, complete the [Twitter OAuth settings] (https://dev.twitter.com/docs/auth/oauth/faq)
```php
$CONSUMER_KEY = '';
$CONSUMER_SECRET = '';
$ACCESS_TOKEN = '';
$ACCESS_TOKEN_SECRET = '';
```
