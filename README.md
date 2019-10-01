# What is this?

This is a place for people interested in Smart Contract development to learn from eachother and the Smart Contracts published to the blockchain.

## Ethics

A lot of the effort here will be put to understand Smart Contracts that are on the public Blockchain. In the quest for knowledge, we may uncover the ability to lock, destroy, or steal Virtual Currency. Because of this fact, this project will have rules and structure to try and best support the community. With some inspiration, I'm mostly making up these rules to serve what I think would be an ethical environment to do this learning. I doubt it's perfect and I'm open to feedback (open an issue).

## Rules

1. Do not share non-public exploits on this project without first following [Responsible Disclosure](#Responsible Disclosure)
2. Do not begin an [Attack](#Attack) audit on this project if the contract does not meet our requirements

### Types of Audits

#### Analysis

Analysis is done to understand the intent of a Smart Contract. This will dive into: What does it do? How does it work? Are there admin privileges? Who do you have to trust, and for what?

Analysis can be done openly on any public Smart Contract.

#### Attack

The goal of an attack audit is to exploit the contract logic to either lock, destroy, or steal funds. Attack audits can only be done if the contract fits one of the following requirements:

1. The Smart Contract has already been exploited and there are no longer funds at risk.
2. The audit happened in a private fork by a trusted group following the [Responsible Disclosure](#Responsible Disclosure) guideline and the disclosure period has ended.
3. Express permission by the contract author(s) was given and the contract is of the nature where the author still has full or indirection control over the contract's funds. If the contract author has no elevated privileges in the contract, the Blockchain owns their code and they have no say over it.

## Responsible Disclosure

Depending on the context of the situation, an ethical action may not be straight forward. Below are a few options I personally find reasonable and ethical. If you disagree or have thoughts, happy to discus (open an issue).

## Option A

After an exploit is found, find the party most responsible for the project. If the contract has an account that can remedy the issue (disable the exploit, update the code), the owner of that account is the responsible party.

1. use reasonable methods to verify they are in fact the responsible party
2. follow their disclosure guidelines if available and reasonable
3. share your plans of disclosure to the responsible party
4. no earlier than 30 days after disclosure, publicly announce the severity of the issue / exploit
5. no earlier than 90 days after disclosure, publicly share details of the issue / exploit

## Option B

1. contact trusted public figures (todo: build list) providing serverity and limited details
2. publicly announce the severity of the issue / exploit alongside trusted figure for crediablity
3. no earlier than 90 days after disclosure, publicly share details of the issue / exploit
4. no earlier than 90 days, run [Option C](#Option C) with remaining funds.

## Option C

1. contact multiple trust worthy people in the community (todo: build list) and share plan
2. setup a multisig wallet with those community members who agree with plan
3. exploit and drain the contract to the mutlisig wallet
4. publicly share intention and members of multi sig wallet
5. use blockchain analysis to determine correct ownership of drained funds
6. deploy fund recovery contract
7. take no more than 10% of value for bounty, if amount is large, 1% may be more appropriate
