Here is a simple flow chart:

test1
test2-4
test3-4

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