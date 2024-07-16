# PHP-Practice
php codes 
<!DOCTYPE html>
<html>
<body>

<?php
$power = 6;
$catch = 1;

if ($power > 1) {
  echo "Batsman tried to hit a ball for a six";
  if ($catch == 1) {
    $dropped = rand(0, 1);
    if ($dropped == 1) {
      echo " and the fielder dropped the ball";
    } else {
      echo " but the fielder caught the ball";
    }
  } else {
    echo " and he succeeded";
  }
  echo $dropped;
}
?>

</body>
</html>
