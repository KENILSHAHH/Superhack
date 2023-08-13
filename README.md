# Superhack

Problem

The major problem with DataDao is that you cannot tailor it to meet the demands of off-chain restrictions, because what's the meaning of on-chain data dao if we need to broadcast their off-chain identity first ! That's when it hit me "ZKP" is the ultimate solution to protect the anonymity of data contributors as well as ease of verifiability for DAO operators. So that's the story behind ZK-DataDao.

Solution

A Data DAO where the dao operator creates the DAO with ZK entry restrictions and multiple contributors can contribute after proving that they are eligible to contribute using ZK-SNARK. After they contribute more than the minimum contributions ( set by the DAO operator ) they will be eligible to get a share of the pool reward after DAO is closed. Every file upload i.e. ( format of contribution, actual contribution ) is done using DealClient.sol contract which utilizes zondax actors. ZKP is done using ZK-SNARK protocol using libraries zokrates, circom, snarkjs Contract integration and wallet client is implemented using Wagmi and viem


Contract Deployed on Zora/Mode/OPtimism/Base testnets
