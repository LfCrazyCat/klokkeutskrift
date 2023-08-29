# klokkeutskrift
Klokketest

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Klokketest</title>
<script>
window.onload = oppdater;

function oppdater() {
    const tid = new Date();
    document.getElementById("klokkeutskrift").innerHTML = tid.
getHours() + ":" + tid.getMinutes() + ":" + tid.getSeconds() ;
setTimeout(oppdater, 1000);
}
</script>
</head>
<body>
<p>Klokka er nå: <span id="klokkeutskrift">Kunne ikke vise tidspunkt</span></p>

</body>
</html>
