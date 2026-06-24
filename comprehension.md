# COMPREHENSION
## Code maintenant compris
#### Dans index.php
``` 
get_all_departments()
foreach($departments as $line)
```
- Appelle de fonction 
- Utilisation de foreach
  
#### Dans dept_form
```
    $dept_no_url = $_GET['dept_no'] ?? '';
```
- si dept_no_url existe alors c'est egale a $_GET['dept_no'] sinon c'est vide
## Code pas encore compris
``` 
    $editing = $dept_no_url !== '' && get_one_department($dept_no_url);

```

## Fonctions non connues
#### Dans index.php 
- urlencode

#### Dans dept_form
- htmlspecialchars
- trim
- 



