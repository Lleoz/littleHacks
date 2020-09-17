# Little Hacks
Pequeños Códigos que nos hacen la vida más fácil :)

## SQL

### Consulta que devuelve cuantos email hay de cada uno

      select email, COUNT(*) Total
      where aprobado = 1
      group By email
      having COUNT(*) > 1
