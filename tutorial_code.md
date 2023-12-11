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
The agent needs to check the water level. Program the agent to check for empty space (air) under it. If there is air under it, the agent must open the water outlet. Build code like this:
```  blocks
if (blocks.testForBlock(GRASS, positions.add(
agent.getPosition(),
pos(0, -4, 0)
))) {
	
}

```
## Step 2
Than program the agent to destroy the marked block. Move it to the right place and destroy the block to release the water. Use ``||AGENT MOVE||`` and ``||AGENT DESTROY||``

### ~ Hint

```  blocks
if (blocks.testForBlock(GRASS, positions.add(
agent.getPosition(),
pos(0, -4, 0)
))) {
    agent.move(RIGHT, 4)
    agent.destroy(FORWARD)
}

```
