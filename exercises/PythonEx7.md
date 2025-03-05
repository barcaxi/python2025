# Python Exercise 7

# Lab #1

1. Open your Pycharm project `Python2025` from your main `python` folder.

1. Create a new weekly project folder called `Ex7` -  (<kbd>File</kbd> ... <kbd>New...</kbd> ... <kbd>Directory</kbd>):

## Part 1 - Basic JSON

1.  In your `Ex7` folder create a Python program called `player1.py` to convert the Python dictionary below to a JSON string and print it:

    ```
    player = {
        "name": "Lionel Messi",
        "club": "Paris Saint-Germain",
        "country": "Argentina",
        "caps": 164,
        "goals": 90
    }    
    ```  
    Expected output:
    ```
    {"name": "Lionel Messi", "club": "Paris Saint-Germain", "country": "Argentina", "caps": 164, "goals": 90}
    ```

    You must use the `json.dump()` function    

1.  In your `Ex7` folder create a Python program called `player2.py` to convert the Python JSON string below to a dictionary and print details from it:

    ```
    player = '{"name": "Pedri", "club": "FC Barcelona", "country": "Spain", "caps": 14, "goals": 0}'
    ```  
    Expected output:
    ```
    - Player dictionary - 
    {'name': 'Pedri', 'club': 'FC Barcelona', 'country': 'Spain', 'caps': 14, 'goals': 0}

    Pedri plays for FC Barcelona and Spain

    ```

    You must use the `json.load()` function    

3.  In your `Ex7` folder create a Python program called `writePlayer.py` to write the player dictionary for Pedri to a JSON file called `player.json`

    Expected contents in `player.json`:
    ```
    {"name": "Pedri", "club": "FC Barcelona", "country": "Spain", "caps": 14, "goals": 0}
    ```

4.  In your `Ex7` folder create a Python program called `updateGoals.py` to allow you to update the goals value in the `player.json` file.

    Expected Output:
    ```
    Input a new value for goals:1

    ```

    Expected contents in `player.json`:
    ```
    {"name": "Pedri", "club": "FC Barcelona", "country": "Spain", "caps": 14, "goals": 1}
    ```

5.  In your `Ex7` folder create a Python program called `updatePlayer.py` to allow you to update the both caps and goals values in the `player.json` file.

    Expected Output:
    ```
    Input a new value for caps (14):15
    Input a new value for goals (1):2

    ```

    > Notice how the current values are shown inside brackets.

    Expected contents in `player.json`:
    ```
    {"name": "Pedri", "club": "FC Barcelona", "country": "Spain", "caps": 15, "goals": 2}
    ```

