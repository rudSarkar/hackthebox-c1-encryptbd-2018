# Solve
* Script Execution Protection (using `exit();` function)
  ```PHP
  <?php
        ...
    if ($_SESSION['admin_loggedin'] !== true) {
    header('Location: /log-in.php');
    exit(header('Location: /log-in.php'));
    }
    ...
  ?>
```

* Script Execution Protection (using `die();` function)
  ```PHP
  <?php
        ...
    if ($_SESSION['admin_loggedin'] !== true) {
    header('Location: /log-in.php');
    die(header('Location: /log-in.php'));
    }
    ...
  ?>
```
