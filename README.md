# Html-Button-Custom
This is a repository for a custom HTML button, 'sign in with Google'.
<!DOCTYPE html>
<html>
<head>
<style>
.button {
    display: inline-block;
    border-radius: 6px;
    transition: all 0.5s;
    cursor: pointer;
    background-color: white;
    border: solid;
    color: black;
    width: 400px;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}

.button:hover {
    box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24),0 17px 50px 0 rgba(0,0,0,0.19);}

.button:active {
  background-color: #e7e7e7;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}

</style>
</head>
<body>

<h2>CSS Buttons</h2>

<button>Default Button</button>
<a href="#" class="button">Sign in with Google</a>
</body>
</html>
