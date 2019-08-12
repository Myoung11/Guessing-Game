/*This program is a guessing game where you can either play and guess the number the
* computer is thinking of or watch the computer try and guess the secret number

*/

#include <iostream>
#include <cstdlib>
#include <ctime>

using namespace std;

int main ()
{
  int randomNumber;  // Computer generated random number to guess
  int randomNumber2; // Computer generated random number for computer's guess
  int userGuess;
  char pickPlayer;   // Variable for p, c, or q

cout << "Would you like to play (p), watch the computer play (c), or quit (q)?: ";
    cin >> pickPlayer;

  srand (time(NULL));               // Sets different seeds to get different random numbers each time
  randomNumber = rand() % 100 + 1;  // Generates the random number between 1-100

if (pickPlayer == 'P' || pickPlayer == 'p') {

    do {

        cout << "Guess a number from 1 to 100: " << endl;
        scanf ("%d",&userGuess);                         // User inputed answer

            if (randomNumber < userGuess) {
                cout << "Too high, guess again." << endl;
                cout << endl;
            }

            else if (randomNumber > userGuess) {
                cout << "Too low, guess again. " << endl;
                cout << endl;
            }

  } while (randomNumber != userGuess);

cout << "Congratulations! The correct number was " << randomNumber << endl;

}

if (pickPlayer == 'C' || pickPlayer == 'c') {

    srand (time(NULL));                // Sets different seeds to get different random numbers each time
    randomNumber = rand() % 100 + 1;   // Random number to guess between 1-100

    randomNumber2 = rand() % 100 + 1;  // The computer's guess between 1-100

   do {


            if (randomNumber < randomNumber2) {
                cout << "The computer's guess is " << randomNumber2 << endl;
                cout << "Too high, guess again." << endl;

                int max = randomNumber2; // Sets the max to what the last guess was
                int min = 1;

                randomNumber2 = (min + (rand() % (int) (max - min +1))); // Generates a random number lower than the last guess
                cout << endl;
            }

            else if (randomNumber > randomNumber2) {
                cout << "The computer's guess is " << randomNumber2 << endl;
                cout << "Too low, guess again. " << endl;

                int max = 100;
                int min = randomNumber2; // Sets the min to what the last guess was

                randomNumber2 =  (min + (rand() % (int) (max - min + 1))); // Generates a random number higher than the last guess
                cout << endl;
            }

  } while (randomNumber != randomNumber2);

cout << "The computer's guess is " << randomNumber2 << endl;
cout << "Congratulations! The correct number was " << randomNumber << endl;

}

if (pickPlayer == 'Q' || pickPlayer == 'q') {

    cout << "Thank you for playing!" << endl;
    return 0;
}

while (randomNumber == randomNumber2 || randomNumber == userGuess){ // While statement to run the program again when the correct number is guessed

    cout << "Would you like to play (p), watch the computer play (c), or quit (q)?: ";
    cin >> pickPlayer;

  srand (time(NULL));               // Sets different seeds to get different random numbers each time
  randomNumber = rand() % 100 + 1;  // Generates the random number between 1-100

if (pickPlayer == 'P' || pickPlayer == 'p') {

    do {

        cout << "Guess a number from 1-100: " << endl;
        scanf ("%d",&userGuess);                         // User inputed answer

            if (randomNumber < userGuess) {
                cout << "Too high, guess again." << endl;
                cout << endl;
            }

            else if (randomNumber > userGuess) {
                cout << "Too low, guess again. " << endl;
                cout << endl;
            }

  } while (randomNumber != userGuess);

cout << "Congratulations! The correct number was " << randomNumber << endl;

}

if (pickPlayer == 'C' || pickPlayer == 'c') {

    srand (time(NULL));                // Sets different seeds to get different random numbers each time
    randomNumber = rand() % 100 + 1;   // Random number to guess between 1-100

    randomNumber2 = rand() % 100 + 1;  // The computer's guess between 1-100

   do {


            if (randomNumber < randomNumber2) {
                cout << "The computer's guess is " << randomNumber2 << endl;
                cout << "Too high, guess again." << endl;

                int max = randomNumber2; // Sets the max to what the last guess was
                int min = 1;

                randomNumber2 = (min + (rand() % (int) (max - min +1))); // Generates a random number lower than the last guess
                cout << endl;
            }

            else if (randomNumber > randomNumber2) {
                cout << "The computer's guess is " << randomNumber2 << endl;
                cout << "Too low, guess again. " << endl;

                int max = 100;
                int min = randomNumber2; // Sets the min to what the last guess was

                randomNumber2 =  (min + (rand() % (int) (max - min + 1))); // Generates a random number higher than the last guess
                cout << endl;
            }

  } while (randomNumber != randomNumber2);

cout << "The computer's guess is " << randomNumber2 << endl;
cout << "Congratulations! The correct number was " << randomNumber << endl;

}

if (pickPlayer == 'Q' || pickPlayer == 'q') {

    cout << "Thank you for playing!" << endl;
    return 0;
}

}


return 0;
}
