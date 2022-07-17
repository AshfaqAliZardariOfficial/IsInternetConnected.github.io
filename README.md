# [IsInternetConnected](https://ashfaqalizardariofficial.github.io/IsInternetConnected.github.io) 
by ***Ashfaq Ali Zardari*** 
A native JavaScript programming code to check whether internet is connected or not.

## Method and Usage
```
// Is internet connected.
function retry_connection() {
    var msg = document.getElementById("internet_connection");
    var url = "https://raw.githubusercontent.com/AshfaqAliZardariOfficial/IsInternetConnected.github.io/master/1x1.png";
    setInterval(function () {
        $.ajax({
            cache: false,
            url: url,
            type: 'GET',
            timeout: 5000,
            success: function () {
                msg.style.color = "green";
                msg.innerHTML = "Connected to internet!";
                console.log("Connected!");
            },
            error: function () {
                msg.style.color = "red";
                msg.innerHTML = "No connection.";
                console.log("No connection.");
            }
        })
    }, 1000);
}

// Start the magic!
retry_connection();
```
## Contact and Supporting Info
Feel free to contact me on <a href="mailto:ashfaqalizardariofficial@gmail.com" target="_blank" title="ashfaqalizardariofficial@gmail.com"><img src="https://ssl.gstatic.com/ui/v1/icons/mail/rfr/logo_gmail_lockup_default_1x_r2.png" alt="ashfaqalizardariofficial@gmail.com" width="70" /></a>  
  
  <a href="https://paypal.me/ashfaqalizardari247?country.x=CA&locale.x=en_US" target="_blank" title="paypal.me/ashfaqalizardari247"><img src="https://www.paypalobjects.com/paypal-ui/logos/svg/paypal-color.svg" alt="PayPalMe" width="160" /></a>    <a href="https://www.buymeacoffee.com/ashfaqalizardari" target="_blank" title="buymeacoffee.com/ashfaqalizardari"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" width="160" /></a>

