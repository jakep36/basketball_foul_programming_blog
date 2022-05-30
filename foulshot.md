## Player was fouled in an NBA Game

## Do they get free throws?

```mermaid
flowchart TD
  A[Player Was Fouled]
  A -->fouled{Shooting?}
  fouled --> shooting[Yes]
  fouled --> not-shooting[No]
  shooting --> make-it{Make it?}
  make-it --> made-it[Yes]
  make-it --> missed-it[No]
  made-it --> shot[One free throw]
  missed-it --> three{Three pointer?}
  three --> yes-three[Yes]
  three --> no-three[No]
  yes-three --> three-shots[Three free throws]
  no-three --> two-shots[Two free throws]
  not-shooting --> bonus{In the bonus?}
  bonus --> yes-bonus{In the double-bonus?}
  yes-bonus --> yes-double-bonus[Two free throws]
  yes-bonus --> no-double-bonus[One-and-one free throws]
  bonus --> no-bonus[No free throws]
```
