# jsprogramming
## editing the file
variable
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scoped Variables</title>
</head>
<body>
    <h1>Scope Lab for Var, Let and Const</h1>
    </h1>
    <script src="./scope_lab.js"></script>
</body>
</html>
The above HTML code has one <h1> tag in file and one <script> tag to include js file in scope_lab.html file using the src attribute.
// Global scope
var globalVar = "I'm a global variable";
let globalLet = "I'm also global, but scoped with let";
const globalConst = "I'm a global constant";


{
// Block scope
var blockVar = "I'm a block-scoped var";
let blockLet = "I'm a block-scoped let";
const blockConst = "I'm a block-scoped const";
}
