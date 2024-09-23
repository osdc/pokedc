# Pokedc
Add your pokemon entries here for them to be visible on [pokedex.osdc.dev](https://pokedex.osdc.dev/)!

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
    - A number for your pokemon (between 1 and 600);
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
6. Commit your changes:
    ```
    git commit -m "Add new pokemon entry"
    ```
7. Push Changes to github:
    ```
    git push origin main
    ```
8. Open a pull request: Check if everything has gone right so far and open a pull request!