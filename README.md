### EX NO : 01
# <p align="center">MDP REPRESENTATION</p>

## AIM:
To represent any one real-world problem in MDP form.

## PROBLEM STATEMENT:

### Problem Description :
Suicide Pod was launched in Switzerland. Their government is trying to normalise it. Reinforcement learning can be introduced to confirm the efficiency of the pod.
![image](https://github.com/Jovita08/mdp-representation/assets/94174503/84c3433d-f987-4b36-b2ce-5cda9b107ed8)

### State Space :
{Alive, Rest, Dead} -> {0,1,2}
</br></br>
### Sample State :
Alive

### Action Space :
{Releasing right amount of nitrogen, Releasing low nitrogen} -> {0,1}

### Sample Action : 
Releasing right amoount of nitrogen

### Reward Function :
```
R={ +1 , right amount of nitrogen
     0 , otherwise
  }
```
</br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br></br>
### Graphical Representation :
![image](https://github.com/NITHISHKUMAR-P/mdp-representation/assets/93427017/502b4b83-f11a-4cf5-bdf8-7bfa7b6d45ff)


## PYTHON REPRESENTATION:
Developed By : **Nithishkumar P**
</br>
Register No. : **212221230070**
```py
P={0: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 0, 0.0, True)]},
   1: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 2, 1.0, True)]},
   2: {0: [(1.0, 2, 0.0, True)],
       1: [(1.0, 2, 0.0, True)]}}
```
## OUTPUT:
![image](https://github.com/NITHISHKUMAR-P/mdp-representation/assets/93427017/690df3c9-9d9e-4a32-b420-076aacb656e2)

## RESULT:
Thus, a real-world problem is represented in MDP form.
