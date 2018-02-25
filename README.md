# BulkUnfollow

If you are using Chrome browser, go to developer tools and paste the below code in the console:
=====================================
var buttons = $("button"),
interval = setInterval(function(){
	var btn = $('.is-following');
   	console.log("Clicking:", btn);
    btn.click();
    if (buttons.length === 0) {
    	clearInterval(interval);
    }
}, 10);
=====================================

This will click on 'unfollow' button on your current webpage.
