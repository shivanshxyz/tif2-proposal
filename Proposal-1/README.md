# Proposal-1 : BlockTez - A no code tool to create smart contracts on Tezos

## Problem Statement

I was looking into ways to make tezos community a more inclusive by making a path for new builders who are not programers by creating a no-code tool for creating smart contracts. No-code is going to open a wave of interest in tech among people who might not be expected to be builders. Think lawyers, consultants, marketers, young children, home-makers, artists. And they will build the most creative projects that transform their fields.

To implement a smart contract, profound programming knowledge and skills in the programming language is required. Non-computer specialists or untrained users with little programming knowledge have a hard time comprehending the contracts, interpreting their meaning and predicting the automated actions.

## Solution

- Use Blockly framework to create a visual editor to create smart contracts using drag and drop components. Blockly was made by Google to create visual programming languages. MIT app inventor is one of the most famous use cases of the Blockly framework.

- I will use blockly to convert Blockly code into LIGO contracts. For that I will have to write a custom interpreter layer for LIGO which will convert Blockly blocks into LIGO contracts since Blockly itself is not a programming language.

- I will use create custom drag and drop components based on the semantics of LIGO to make it usable.

## Tech Stack Required

- Nodejs
- Typescript
- Ligo
- Docker

## Past attempts for similar idea

- Someone has attempted a similar proof of concept for solidity using blockly. Even though the project was abandoned by the maintainer, it still feels very polished for the limited features it provides. (https://github.com/JMLX42/blockly-solidity)
