Here is a simple flow chart:

test1
test2-11-1-12
test3-4-11

```mermaid
gitGraph
   commit
   commit
   branch develop
   checkout develop
   commit
   commit

   branch staging
   checkout staging
   commit
   commit
   
   checkout main
   merge develop
   commit
   commit

```