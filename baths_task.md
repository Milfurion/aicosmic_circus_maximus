# Activate the Radio Tower
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```
```template
   //     
```


## Step 1

We need to automate the water level control system in the Bath of Caracalla. If the water is too low, the agent must open a hole allowing the water to flow out and raise the level.

### ~ Hint 
To check the water level, check if there is air in a few blocks under the agent. Use ``||if||`` and ``||test for||``  for to do this. 

```  blocks
if (blocks.testForBlock(AIR, pos(0, -4, 0))) {
    agent.destroy(FORWARD)
}
if (blocks.testForBlock(AIR, pos(0, -3, 0))) {
    agent.move(RIGHT, 2)
    agent.destroy(FORWARD)
}
if (blocks.testForBlock(AIR, pos(0, -2, 0))) {
    agent.move(RIGHT, 3)
    agent.destroy(FORWARD)
}
if (blocks.testForBlock(AIR, pos(0, -1, 0))) {
    agent.move(RIGHT, 2)
    agent.destroy(FORWARD)
}
         
})
```

