

# Blockchain Project

Welcome to the **Blockchain Project**, a basic implementation of a blockchain in Python, aimed at demonstrating core blockchain concepts such as block creation, proof of work, and hashing. This project is part of my learning journey and serves as an introduction to blockchain technology, using Flask to display the blockchain in a simple web interface.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [How It Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)

---

## About the Project

This project is designed to give a hands-on understanding of how a blockchain operates, focusing on the creation of blocks, proof of work, and validating the chain. The project uses:

- **Python** for the backend logic.
- **Flask** to create a basic web application.
- **Hashlib** for cryptographic operations like hashing the blocks.
- **Datetime** to timestamp blocks.

---

## Features

- **Blockchain creation**: Dynamically adds new blocks with proofs and timestamps.
- **Proof of Work**: Implements a simple proof of work algorithm to secure the blockchain.
- **Hashing**: Uses SHA-256 for hashing block data.
- **Web Interface**: Displays the blockchain through a simple Flask app.

---

## How It Works

1. **Block Creation**: A block is added to the blockchain with a unique proof and the hash of the previous block.
2. **Proof of Work**: To maintain the integrity of the blockchain, each new block requires a proof, which is found through computational work (solving a mathematical problem).
3. **Hashing**: Each block’s contents are hashed to create a unique fingerprint, making the blockchain secure and tamper-resistant.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Blockchain-Project-IGCSE.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Run the Flask app:
   ```bash
   python app.py
   ```
2. Access the blockchain interface through `http://127.0.0.1:5000/`.

---

## Code Structure

- `app.py`: The main file containing the Flask application and blockchain logic.
- `blockchain.py`: Contains the Blockchain class with methods for block creation, proof of work, hashing, and chain validation.

---

## Contributing

Feel free to contribute to this project! You can improve the code, add new features, or fix bugs. Please make sure to fork the repository and create a pull request with your changes.

---

## License

This project is open-source and available under the MIT License.

---

## About Me

Hey, I'm **Bayazid**—a 16-year-old from Bangladesh with a passion for coding, web development, and blockchain technology. I am currently working on improving my JavaScript and Python skills while diving into game development and ethical hacking. I'm also active in the programming community on platforms like Sololearn and GitHub.

This repository is part of my journey in exploring new skills, including blockchain, to eventually work on projects that could help me grow professionally and personally. 

I also spend a lot of time participating in online communities, including being the head mod of a Discord server, and am working on increasing my physical fitness and height through consistent exercise plans.

If you have any questions or suggestions for this project, feel free to reach out or contribute directly!

