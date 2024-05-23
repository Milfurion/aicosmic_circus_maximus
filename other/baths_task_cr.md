# Kontrolirajte razinu vode
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
     
```
```template
   //     
```


## Korak 1

Moramo automatizirati sustav kontrole razine vode u Caracallinoj kupelji. Ako je vode prenisko, sredstvo mora otvoriti rupu kako bi voda mogla istjecati i podići razinu.

### ~ Savjet
Uništi sve označene blokove u jednom potezu!

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

