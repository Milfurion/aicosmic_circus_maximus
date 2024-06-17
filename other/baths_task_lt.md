# Kontrolēt ūdens līmeni
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
     
```
```template
   //     
```


## Step 1

Mums jāautomatizē ūdens līmeņa kontroles sistēma Karakallas vannā. Ja ūdens līmenis ir pārāk zems, aģentam ir jāatver caurums, kas ļauj ūdenim izplūst un paaugstināt līmeni.

### ~ Padoms 
Iznīcini visus atzīmētos blokus vienā piegājienā!

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

