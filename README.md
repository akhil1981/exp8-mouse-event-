<!DOCTYPE html>

<html>

<head>

<script>

function bgChange(bg) {

document.body.style.background = bg;

}

</script>

</head>

<body>

<h2>Change background color</h2>

<p>Mouse over the squares!</p>

<table style="width:600px;height:300px">

<tr>

<td onmouseover="bgChange(this.style.backgroundColor)"

onmouseout="bgChange('transparent')"

style="background-color:pink">

</td>

<td onmouseover="bgChange(this.style.backgroundColor)"

onmouseout="bgChange('transparent')"

style="background-color:PaleGreen">

</td>

<td onmouseover="bgChange(this.style.backgroundColor)"

onmouseout="bgChange('transparent')"

style="background-color:Blue">

</td>

</tr>

<tr>

<td onmouseover="bgChange(this.style.backgroundColor)"

onmouseout="bgChange('transparent')"

style="background-color:yellow">

</td>

<td onmouseover="bgChange(this.style.backgroundColor)"

onmouseout="bgChange('transparent')"

style="background-color:Green">

</td>

<td onmouseover="bgChange(this.style.backgroundColor)"

onmouseout="bgChange('transparent')"

style="background-color:gray">

</tr>

</table>

</body>

</html>
