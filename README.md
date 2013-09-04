adblocker-detector
==================

**adblocker-detector** is a tiny javascript function for detecting whether or not your visitors are using an ad blocker.

Example usage:

	detectAdBlock(function(active){
    	if (active) {
        	alert('AdBlocker not detected. All clear');
    	}
    	else {
        	alert('AdBlocker detected!');
    	}
	});


Enjoy!