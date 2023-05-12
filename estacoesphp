<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<?php
function getSeason($month, $day) {
    if (($month == 3 && $day >= 20) || ($month > 3 && $month < 6) || ($month == 6 && $day < 21)) {
        return 'Primavera';
    } elseif (($month == 6 && $day >= 21) || ($month > 6 && $month < 9) || ($month == 9 && $day < 23)) {
        return 'Verão';
    } elseif (($month == 9 && $day >= 23) || ($month > 9 && $month < 12) || ($month == 12 && $day < 21)) {
        return 'Outono';
    } else {
        return 'Inverno';
    }
}

// Obtém a data atual
$currentDate = new DateTime();
$month = $currentDate->format('n');
$day = $currentDate->format('j');

// Determina a estação do ano
$season = getSeason($month, $day);

// Exibe a estação do ano
echo 'Estamos na estação: ' . $season;
?>
</body>
</html>