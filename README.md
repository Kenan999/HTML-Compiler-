<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@3.4.1/dist/css/bootstrap.min.css" integrity="sha384-HSMxcRTRxnN+Bdg0JdbxYKrThecOKuH5zCYotlSAcp1+c8xmyTe9GYg1l9a69psu" crossorigin="anonymous">
    <title>Document</title>

    <script>
        function compoilerHTML(field,e){
            document.getElementById("output").innerHTML=field.value;
        }
    </script>

    <style>
       textarea, #output{
        background-color: rgb(21,32,43);
        width: 80%;
        height: 150px;
        color: aliceblue;
        margin: auto;
         display: block;
         margin-top: 20px;
         border-radius: 30px;
       } 

    </style>

</head>


<body>
   
        <div>
            <h1 class="d-block p-2 bg-primary text-white text-center "   >LIVE HTML COMPILER!</h1>
        </div>
       
        <section>
            <textarea   type="text"
            placeholder="    WRITE SOME HTML HERE!!!" 
            
            onkeyup="compoilerHTML(this)"></textarea>
       
       
    
        <div id="output"> </div>
        </section>
     


  

</body>
</html>
