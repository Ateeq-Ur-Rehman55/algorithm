Runoff.c

This is rank-choice voting system. A ranked-choice system, voters can vote for more than one candidate. Instead of just voting for their top choice, they can rank the candidates in order of preference.

Installation

Follow these steps to install and run the program:

    Clone the repository:


git clone https://github.com/yourusername/runoff.c.git

Navigate to the project directory:

code runoff.c

Compile the program using gcc:

    gcc -o runoff runoff.c

Usage

To run the program, use the following command format:


./runoff candidate1 candidate2 candidate3 ...

Example

    Compile the program:

gcc -o runoff runoff.c

Run the program with candidate names:

./runoff Alice Bob Charlie

The program will prompt you to enter the number of voters:


Number of voters: 3

Enter the candidate name by rank:

rank1: Alice
rank2: Bob
rank3: Charlie

rank1: Bob
rank2: Alice
rank3: Charlie

rank1: Alice
rank2: Bob
rank3: Charlie

The program will then output the winner(s) of the election:

bash

    Winner: Alice

Features

    Accepts candidate names as command-line arguments.
    Prompts for the number of voters.
    Takes ranks by condidate name.
    Determines the winner(s).

Contributing

We welcome contributions to improve this program. Here’s how you can contribute:

    Fork the repository.
    Create a new branch (git checkout -b feature/YourFeature).
    Commit your changes (git commit -m 'Add some feature').
    Push to the branch (git push -u origin feature/YourFeature).
    Open a pull request.

Contact

For any questions or feedback, please reach out via:

    Email: ateeqsarwarkhand@gmail.com
    Instagram: ateeq_ur_rehman55

