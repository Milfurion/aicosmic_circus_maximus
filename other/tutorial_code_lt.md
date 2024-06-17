# Control the water level
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
     
```
```template
   //     
```


## Step 1
Ieprogrammējiet aģentu, lai iznīcinātu atzīmēto bloku. Pārvieto to uz pareizo vietu un iznīcini bloku, lai atbrīvotu ūdeni. Izmantojiet ``||AGENT MOVE||`` un ``||AGENT DESTROY||``

### ~ Pārbaudiet mājienu

```  blocks
agent.move(RIGHT, 4)
agent.destroy(FORWARD)

```
