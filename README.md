<h1 align="center">
  
 [![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2327F797&center=true&vCenter=true&lines=echo+%22Hello+my+name+is+Bozhidar!%22)](https://git.io/typing-svg)
  
</h1>

<h3 align="center">😎 About me</h3>

```php
dbh.php
<?php

$servername = "Bozhidar";
$dBUsername = "Don't have";
$dBAge = "19";
$dBMusic = "Metal enjoyer";

$conn = mysqli_connect($servername, $dBUsername, $dBAge, $dBMusic);

if (!$conn) {
	die();
} else {
	header("Location: my_hobbies_and_work.php");
}
```

<hr>
<br>
<h3 align="center">💻 Hobbies and Work</h3>

```php
my_hobbies_and_work.php
<?php

require "dbh.php";

function hobbies_and_work($conn) {

  $hobbies = "I like playing competitive games and programming";
  $current_work = "Currently working on notemanager with Valeri Ivanov 🕵️🕵️";
  $currently_learning = "JavaScript";
  $my_projects = "Company website and personal projects";
  $reach_me = "bpboyadzhiev20@codingburgas.bg";
  
  $languages = [
    array("programming_languages", "PHP", "C++"),
    array("frontend_languages", "Bootstrap5", "CSS3", "HTML5"),
    "database" => "mysqli"
  ];

  return true;
}
```

<hr>
<br>

<h3 align="center">🏆 Stats</h3>
  <div align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=BozhidarBoyadzhiev&theme=dark&show_icons=true" height="180">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BozhidarBoyadzhiev&layout=compact&theme=dark"  height="180">
  </div>
  
<hr>
<br>

<div align="center">
  <img src="https://shields-io-visitor-counter.herokuapp.com/badge?page=BozhidarBoyadzhiev.BozhidarBoyadzhiev">
</div>
