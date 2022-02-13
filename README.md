# dom-lessons-junjiel4616

<html>
    <head>
        <script src="https://jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.mini.js"></script>
        <body>
            <button>Hi there</button>
            <h2></h2>
            <h3>no stop, dont touch!</h3>
            <script>
                document.querySelector("button").addEventListener("click",function(){
                    var name = prompt("Who is the one that has awakened me?");
                    document.querySelector("h2").innerHTML = "Hi, " + name
                });
                
                document.addEventListener("keypress",function(){
                    alert("cool you pressed a key");
                });
                
                document.addEventListener("mousedown",function(){
                    alert("oh noooo");
                });
            </script>
        </body>
    </head>
</html>
