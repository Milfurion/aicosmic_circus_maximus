# Controlla il livello dell'acqua
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
     
```
```template
   //     
```


## Passo 1

Dobbiamo automatizzare il sistema di controllo del livello dell'acqua nelle Terme di Caracalla. Se l'acqua è troppo bassa, l'agente deve aprire un foro che consenta all'acqua di defluire e alzare il livello.

### ~ Suggerimento
Distruggi tutti i blocchi contrassegnati in un colpo solo!

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

