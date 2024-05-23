# Controla el nivel del agua
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
     
```
```template
   //     
```


## Paso 1

Hay que automatizar el sistema de control del nivel del agua en las Termas de Caracalla. Si el agua está demasiado baja, el agente debe abrir un orificio por el que salga el agua y subir el nivel.

### ~ Pista
¡Rompe todos los bloques de mármol de una vez!

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

