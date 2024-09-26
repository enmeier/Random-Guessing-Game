flowchart TD
    Start([Start]) --> A["Guess a word"]
    A --> B["rl.setPrompt('Guess a word')"]
    B --> C{"Is it right?"}
    C -->|Yes| D["That is right!"]
    C -->|No| E["That is wrong!"]
    D --> End([End])
    E --> A

    #### For step _one_, you will be prompted to guess a random word
    #### For step _two_, the random word that you are trying to guess >will be prompted
    #### For step _three_, the program will figure out if your guess >right or wrong
    #### For step _four_ and _five_, the program will relay back a message >saying if the message is right or wrong
    #### If the answer is **_right_** then the game will end
    #### If the answer is **_wrong_** then the game will restart
