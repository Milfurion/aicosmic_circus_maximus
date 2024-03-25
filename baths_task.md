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

We need to automate the water level control system in the Bath of Caracalla. If the water is too low, the agent must open a hole allowing the water to flow out and raise the level.

### ~ Hint 
Destroy all marked blocks in one go!

```  blocks
agent.destroy(FORWARD)
agent.move(RIGHT, 2)
agent.move(UP, 1)
agent.destroy(FORWARD)
agent.move(RIGHT, 3)
agent.move(DOWN, 2)
agent.destroy(FORWARD)
agent.move(RIGHT, 2)
agent.move(UP, 1)
agent.destroy(FORWARD)

```

