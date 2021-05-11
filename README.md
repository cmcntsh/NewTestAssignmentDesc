# NewTestAssignmentDesc
## Step 1
Create a list called candidates which has the individuals who are running for president.
<details>
  <summary>Solution</summary>
  
  ### Solution
  `candidates = ['Aragorn','Arwen','Bilbo','Elrond','Faramir','Frodo','Gandalf','Gimli','Gollum', 'Legolas','Saruman']`
</details>

## Step 2 
Create some simulated ballots. 
<details>
  <summary>Solution</summary>
  
  ### Solution
  ```
  import random

  ballots = []
  ballots_count = 20

  for i in range (0,ballots_count):
      random_number = random.randint(1, len(candidates))
      ballots.append(random.sample(candidates,random_number))
  ```
