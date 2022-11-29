<!DOCTYPE html>
<html>
<head>
    <script async type="text/javascript" src="https://relay.errlog.io/js/v1?apikey={your-api-key}"></script>
    <title>Hello World</title>
    <script type="text/javascript">
		function createError() {
			console.log("We'll generate an error by accessing an undefined variable as if it's a function");
			var param = "Hello Error";
			thisisanerror(param);
		}
    </script>
</head>
<body>
    <h1>Hello World!</h1>
    <div>
        <p>First, ensure you've included your API key in the script tag - replace the text {<span>your-api-key</span>} with your actual API key, which can be found here.</p>
        <p>Now you're ready to capture errors with ErrLog.IO. Try it now:</p>
        <p><button onclick="createError()">Create Error</button></p>
    </div>
</body>
</html>
