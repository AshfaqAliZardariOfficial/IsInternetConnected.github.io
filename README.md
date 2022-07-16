# [IsInternetConnected](IsInternetConnected.github.io) 
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
