# Tubes1_metiuganteng

## Table of Contents

- [General Info](#general-information)
- [Requirements](#requirements)
- [Usage](#usage)
- [Programming Language Used](#languages)
- [Contacts](#contact)

## General Information <a name="general-information"></a>

A program designed to provide a bot's logic in the game 'Diamonds'. The logic uses greedy approach, considering the value of diamonds, the distance from the bot's current position to the target objects, the time taken to reach an object relative to the time remaining, and the existence of other player's bots to find the best opportunity to perform a tackle.
Contributors :

1. 13522029 Ignatius Jhon Hezkiel Chan
2. 13522043 Daniel Mulia Putra Manurung
3. 13522093 Matthew Vladimir Hutabarat

## Requirements <a name="requirements"></a>

### Node.js

You can install Node.js through the following url
[Node.js](https://nodejs.org/en)

### Docker Desktop

You can install Docker Desktop through the following url
[Docker](https://www.docker.com/products/docker-desktop/)

### Yarn

You can run the following command

```cmd
npm install --global yarn
```

### Game Engine

You can see the full guide on setting up the game engine in: [GameEngine](https://docs.google.com/document/d/1L92Axb89yIkom0b24D350Z1QAr8rujvHof7-kXRAp7c/edit)

## Usage <a name="usage"></a>

This section provides guide on how to install the game engine

1. Clone the repository

```cmd
git clone https://github.com/chankiel/Tubes1_metiuganteng.git
```

2. Navigate to the cloned directory

```cmd
cd Tubes1_metiuganteng
cd src
```

3. Install the requirements

```cmd
pip install -r requirements.txt
```

4. Run the bot's logic

```cmd
python main.py --logic <Your_Logic> --email=your_email@example.com --name=your_name --password=your_password --team etimo
```

5. If you wish to run multiple bot with multiple logic, you can alter the script in run-bots.bat accordingly

```cmd
./run-bots.bat
```

## Programming Languages Used <a name="languages"></a>

- Python

## Notes

- If you run multiple bots, make sure each emails and names are unique
- The email could be anything as long as it follows a correct email syntax
- The name, and password could be anything without any space

## Contacts <a name="contact"></a>

Created by [@IgnatiusJHC](https://github.com/chankiel), [@DanielManurung](https://github.com/Gryphuss), dan [@MatthewHutabarat](https://github.com/NgokNgok04)
