from getpass import getpass as input
print("RPS Battle")
Player1Score = 0
Player2Score = 0
while True:
  print("Select your move (R, P or S)")
  Player1Choice = input("Player 1 >").lower()
  Player2Choice = input("Player 2 >").lower()
  if Player1Choice == "r":
    if Player2Choice == "r":
      print("The game is a draw - both players chose rock")
    elif Player2Choice == "s":
      print("Player 1 wins - Player 2's scissors are crushed by Player 1's rock")
      Player1Score += 1
    elif Player2Choice == "p":
      print("Player 2 wins - Player 1's rock is smothered by Player 2's paper")
      Player2Score +=1
  elif Player1Choice == "s":
    if Player2Choice == "r":
      print("Player 2 wins - Player 1's scissors are crushed by Player 2's rock")
      Player2Score +=1
    elif  Player2Choice == "s":
      print("The game is a draw - both players chose scissors")
    elif Player2Choice == "p":
      print("Player 1 wins - Player 2's paper is cut by Player 1's scissors")
      Player1Score += 1
  elif Player1Choice == "p":
    if Player2Choice == "r":
      print("Player 1 wins - Player 2's rock is smothered by Player 1's paper")
      Player1Score +=1 
    elif Player2Choice == "s":
      print("Player 2 wins - Player 1's paper is cut by Player 2's scissors")
      Player2Score += 1
    elif Player2Choice == "p":
      print("The game is a draw - both players chose paper")

  if Player1Score == 3:
    print("Player 1 wins the game!")
    exit()
  if Player2Score == 3:
    print("Player 2 wins the game!")
    exit()
  else:
    continue
