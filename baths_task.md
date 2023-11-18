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
To check the water level, check if there is air in a few blocks under the agent. Use ``||if||`` and ``||test for||``  for to do this. 

```  blocks
if (blocks.testForBlock(AIR, positions.add(
agent.getPosition(),
pos(0, -9, 0)
))) {
    agent.destroy(FORWARD)
}
if (blocks.testForBlock(AIR, positions.add(
agent.getPosition(),
pos(0, -8, 0)
))) {
    agent.move(RIGHT, 2)
    agent.destroy(FORWARD)
}
if (blocks.testForBlock(AIR, positions.add(
agent.getPosition(),
pos(0, -7, 0)
))) {
    agent.move(RIGHT, 3)
    agent.destroy(FORWARD)
}
if (blocks.testForBlock(AIR, positions.add(
agent.getPosition(),
pos(0, -8, 0)
))) {
    agent.move(RIGHT, 2)
    agent.destroy(FORWARD)
}
         
})
```

