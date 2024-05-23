# Ελέγξτε τη στάθμη του νερού
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
     
```
```template
   //     
```


## Βήμα 1

Πρέπει να αυτοματοποιήσουμε το σύστημα ελέγχου της στάθμης του νερού στο Λουτρό του Καρακάλλα. Εάν το νερό είναι πολύ χαμηλό, ο πράκτορας πρέπει να ανοίξει μια τρύπα που να επιτρέπει στο νερό να ρέει έξω και να ανεβάζει τη στάθμη.

### ~ Υπόδειξη
Καταστρέψτε όλα τα μαρκαρισμένα μπλοκ με μία κίνηση!

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

