# Pokedc
Add your Pokemon entries here for them to be visible on [pokedex.osdc.dev](https://pokedex.osdc.dev/)!

## How to add entry:
1. Fork the repository by clicking on the fork button up top.
2. Clone the forked repository on your account: Click on code and then copy the link that shows up. Then go to your terminal and enter the git clone command, it should look something like this:
    ```
    git clone https://github.com/your-name/pokedc.git
    ```
3. Go to the repository directory and then to cdn directory:
    ```
    cd pokedc/cdn/
    ```
4. Create a file, with the name `your_enrol_no.txt`, eg. 22105251.txt
    ### File Structure of txt file:
    - your_name;
    - your_enrol_no;
    - A number for your Pokemon (between 1 and 600);
    - Text you want to display;
        
        (Add a semicolon after each line)

        eg:
        
        Arnav;

        23104173;

        151;

        Hello world!;

5. Stage your added file:
    ```
    git add your_enrol_no.txt
    ```
6. Config your user for this repo:
   ```
   git config user.email 'example@abc.xyz'
   git config user.name 'your-name'
   ```
7. Commit your changes:
    ```
    git commit -m "Add new Pokemon entry"
    ```
8. Create a temporary Personal access token :<br>
   Step 1: Go to the menu button on the top-right of GitHub. <br>
   Step 2: Settings -> Developer Settings -> Personal Access Tokens -> Tokens (classic)<br>
   Step 3: Generate New Token (classic)<br>
   Step 4: Tick [✔️] the Repo option.<br>
   Step 5: generate the token and copy it (don't close the window with the token yet)
      
10. Push Changes to github:
    ```
    git push origin main
    ```
11. If a Windows GitHub login pop-up appears :
        proceed with the sign-in
    Else (if it asks for a username, password) :
        enter your GitHub username.
        enter the token you generated in {step 8} for the password.
    
13. Open a pull request: Check if everything has gone right so far and open a pull request!
    
