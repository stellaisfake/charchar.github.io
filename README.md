<html>
    <body>
        <style>
            body {
               background-color: #253022;
                background-repeat: no-repeat;
                background-size: 100%;
                background-attachment: fixed;
            }
            h1 {
                color: #ae4f2f;
                font-size: 50px;
              
            }
            h2 {
                color: #507844;
                font-size: 50px;
            }
            h3 {
                color: bisque;
                font-size: 25px;
            }

            .accordion {
  background-color: #507844;
  color: #253022;
  cursor: pointer;
  padding: 10px;
  width: 25%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: rgb(182, 220, 181); 
}

.panel {
  padding: 0 18px;
  display: none;
  background-color: #507844;
  overflow-x: hidden;
  overflow-y: hidden;
}
.img {
    height: 300px;
    width: 300px;
    margin-right: 10%;
    position: relative;
  margin-left: 70%;
 vertical-align:middle;
}
.aligned { 
            display: flex;
            align-items:center
        }
          
</style>
</head>
<body>

    <div class="aligned">
        <img src=
"https://images.squarespace-cdn.com/content/v1/59b08d799f7456ac86e35e88/1632526853866-9WEN7V0XBCRJ9UZC6FI6/20190401_Wyeast-002.jpg?format=750w"
            width="150" alt="">
             
        <h1>Charlie Newmann</h1>
    </div>


        
        <h3>2005-2037</h3>
        <button class="accordion">About</button>
<div class="panel">
  <h3>charlie Newmann was born in 2005 I think, he is the best lantern I could ever hope to meet. Charlie was one of the nicest people he used to take his friend camping in his rv and bake, I think he was baking because he always brought a apron and seasoning. Charlie is also my dad, he is the father of me. Sadly charile has been diagnosed with b.i.g, if you did'nt know it stands for big (he is very tall.) 
  </h3> <p>"oh hey sir" -Charile Newmann</p> <img src="https://i.ytimg.com/vi/kb5NtD6-yqU/maxresdefault.jpg">
</div>

        <script>
            var acc = document.getElementsByClassName("accordion");
            var i;
            
            for (i = 0; i < acc.length; i++) {
              acc[i].addEventListener("click", function() {
                this.classList.toggle("active");
                var panel = this.nextElementSibling;
                if (panel.style.display === "block") {
                  panel.style.display = "none";
                } else {
                  panel.style.display = "block";
                }
              });
            }
            </script>
</body>
</html>
