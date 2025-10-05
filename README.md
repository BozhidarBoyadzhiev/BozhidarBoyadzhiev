<h1 align="center">
  
 [![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2327F797&center=true&vCenter=true&lines=echo+%22Hello+my+name+is+Bozhidar!%22)](https://git.io/typing-svg)
  
</h1>

<h3 align="center">😎 About me</h3>

```php
dbh.php
<?php

$servername = "Bozhidar";
$dBUsername = "Boyan";
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
  $current_work = "Not doing anything at the moment";
  $currently_learning = "WPF";
  $my_projects = "Company website and personal projects";
  $reach_me = "bozhidar.p.boyadzhiev@gmail.com;
  
  $languages = [
    array("programming_languages", "C#", "PHP", "C++"),
	array("frameworks", "Entity Framework", "ASP.NET Core"),
    array("frontend_languages", "Bootstrap5", "CSS3", "HTML5"),
    "database" => "MySQLi", "Microsoft Sql Server"
  ];

  header("Location: my_projects.php");
}
```
<h3 align="center">🚀 My Projects</h3>
