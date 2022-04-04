# 0xPlace

*An on-chain version of [r/place](https://www.reddit.com/r/place/).*

## Introduction

[Here's](https://twitter.com/Aella_Girl/status/1510721564861468678?s=20&t=wPpPZnyeR1LosTsUCrSApw) a thread on why r/place is one of the most beautiful projects on the internet. 

We can build a decentralized, permissionless version of r/place on the EVM. This repo is an attempt to do so. 

## Details

We initiate a 1000x1000 blank grid in the contract. 

To place a pixel, the user connects their wallet, chooses an (x,y) location for 0<=x<=1000 and 0<=y<=1000, selects an RGB color, and submits their transaction. We require that the user has not placed a pixel in the last 20 eth blocks.