<!DOCTYPE html>
<html>
<head>
<title> Buat BB </title>
<style>
   body {
    background-color: #FFFFFF;
   }
</style>

<script type="text/javascript">
flag=1
function f1()
{
    alert("thank you bb. xoxo")
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1 align="center"> Assalamualaikum <h1>
<img alt="Stitch" src="https://i.pinimg.com/originals/67/1b/8d/671b8d60d65c3d6fa7012e3e978aceaa.gif" height="200" style="display:block; margin:auto;" />
<h1 align="center">Bby, maap ya soal kemarin, sudah bikin bete, jangan marah yaah.. huhu </h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" dimaapin " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" gak dimaapin " onMouseOver="f()" />
</div>

</body>
</html>
