Here is a simple flow chart:

test1

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