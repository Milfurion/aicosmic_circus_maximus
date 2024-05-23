# Controleer het waterniveau
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
     
```
```template
   //     
```


## Stap 1

We moeten het controlesysteem voor het waterniveau in het Bad van Caracalla automatiseren. Als het water te laag staat, moet de agent een gat openen waardoor het water eruit kan stromen en het niveau omhoog kan.

### ~ Tip
¡Destruye todos los bloques marcados de una vez!

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

