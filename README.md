<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project Backend

NFTime is a simple NFT marketplace that makes buying, selling, and minting NFTs easy.

NFTime is a fast Dapp built on sepolia testnet, it comes with a great user interface to make it easy for users to interact with the market.

We used blockchain technology, the ethereum network, and smart contract development technology to achieve our goal.

The smart contract is written in [solidity](https://soliditylang.org/), and we used JS/TS to test and interact with the contract.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

The smart contract is built using hardhat framework, ethersjs and some other packages and dependencies that speeds up in development process.

* [![Soliditylang][Solidity]][Solidity-url]
* [![Hardhat][Hardhat]][Hardhat-url]
* [![Chainlink][Chainlink]][Chainlink-url]
* [![Openzeppelin-contracts][Openzeppelin]][Openzeppelin-url]

Our interface is designed with the latest technology in web development, and we made it clear and simple so that it would be easy for users to use Dapp without any difficulties.

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![MUI.com][MUI]][MUI-url]
* [![Moralis.io][Moralis]][Moralis-url]
* [![Mongo][MongoDB]][MongoDB-url]
* [![Mongoose][Mongoose]][Mongoose-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how to run the market locally on your computer.

### Prerequisites

You need to check if nodejs and npm are installed on your computer first.

```sh
npm --version
```

```sh
node --version
```

If you don't have node, you can install it from there [official website](https://nodejs.org/en)


### Installation

Below is an example of how to start interacting with the NFT marketplace contract locally.

1. Clone the repo
   ```sh
   git clone https://github.com/HieuSerend/NFTime
   ```
2. Install NPM packages in backend 
   ```sh
   cd NFTime
   npm install
   ```
3. Install NPM packages in frontend 
   ```sh
   cd NFTime-interface
   npm install
   ```  
3. Rename `.env.sample` and `.env.local.sample` file to `.env` and `.env.local`
4. Get the required API keys and information and add it to the `.env` and `.env.local` file.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

You can interact with the smart contract on the local network now.

- `npm run compile` to compile the solidity code
- `npm run deploy` to deploy the contract on the hardhat network
- `npm run test` to run the unit testing of the contract

Run frontend in NFTime-interface.

- `npm run dev`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

This project is under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

We used some web services, open source projects and packages that helps us in our development process, which will be listed down below.

We would like to apologize if we used a free package or service and forgot to mention it.

* [Sepolia Testnet](https://sepolia.dev/)
* [Best README Template](https://github.com/othneildrew/Best-README-Template)
* [Chainlink Contracts](https://www.npmjs.com/package/@chainlink/contracts)
* [Pinata SDK](https://github.com/PinataCloud/Pinata-SDK)
* [solhint](https://github.com/protofire/solhint)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[product-screenshot]: images/screenshot.png

[Solidity]: https://img.shields.io/badge/solidity-363636?style=for-the-badge&logo=solidity&logoColor=white
[Solidity-url]: https://soliditylang.org/
[Hardhat]: https://img.shields.io/badge/hardhat-FFF100?style=for-the-badge&logoColor=black
[Hardhat-url]: https://hardhat.org/
[Chainlink]: https://img.shields.io/badge/chainlink-375BD2?style=for-the-badge&logo=chainlink&logoColor=white
[Chainlink-url]: https://chain.link/
[Openzeppelin]: https://img.shields.io/badge/open_zeppelin-412991?style=for-the-badge&logo=openzeppelin&logoColor=white
[Openzeppelin-url]: https://www.openzeppelin.com/contracts

[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[MongoDB]: https://img.shields.io/badge/mongo_DB-47A248?style=for-the-badge&logo=mongodb&logoColor=white
[MongoDB-url]: https://www.mongodb.com/
[mongoose]: https://img.shields.io/badge/mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white
[mongoose-url]: https://mongoosejs.com/
[MUI]: https://img.shields.io/badge/mui-007FFF?style=for-the-badge&logo=mui&logoColor=white
[MUI-url]: https://mui.com/
[Moralis]: https://img.shields.io/badge/moralis-02d1ae?style=for-the-badge&logo=moralis&logoColor=white
[Moralis-url]: https://moralis.io/


