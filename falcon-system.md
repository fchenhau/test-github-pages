<div class="align-center"><img width="200" src="/img/logo.png" alt="logo"/></div>

# > Falcon System <

## Repu
## List of Abbreviations
| Abbreviations                   | Definition                                                                                 |
| -----------------------------   | -------------------------------------------------------------------------------------------|
| **FGT**                         | Falcon Gateway Token                                                                       |
|                                 |                                                                                            |
| **Content ID**                  | Each content created will have their own unique ID                                         |
|                                 |                                                                                            |
| **Content Message**             | Each of the message being stored as a content                                              |
|                                 |                                                                                            |
| **Web3 Address**                | The unique public key cryptocurrency identified that point to a wallet                     |
|                                 |                                                                                            |
| **Content Owner Address**       | The Web3 address that created the content                                                  |
|                                 |                                                                                            |
| **Content Parent ID**           | The Parent ID of the content                                                               |
|                                 |                                                                                            |
| **Child Content ID**            | The unique ID whereby created under the Parent Content                                     |
|                                 |                                                                                            |
| **Child Content Message**       | The Content Message whereby created under the Parent Content                               |
|                                 |                                                                                            |
| **Private Content Message**     | Only Content Owner Address of the Content Message can continue to create a Child Content Message|
|                                 |                                                                                            |
| **Public Content Message**      | Anyone can continue create Child Content Message under the Public Content Message                           |
## Introduction

**Repu** is a DApp which allows the community to identify if a certain record/content is fake, fraudulent or a scam. Every data will be stored in the blockchain via smart contracts and be allowed to be voted by the community.

Each of the action will cost a certain amount of **FGT** to reduce spamming.

| Action                        | Cost (FGT) | Description                      |
| ----------------------------- | ---------- | -------------------------------- |
| Creating Content              | 100        | Creating new content             |
|                               |            |                                  |
| Set Content Public            | 100        | Set content as public            |
|                               |            |                                  |
| Set Content Private           | 100        | Set content as private           |
|                               |            |                                  |
| Vote Content Up               | 10         | Voting content up                |
|                               |            |                                  |
| Vote Content Down             | 10         | Voting content down              |
|                               |            |                                  |
| Remove Content Vote Down      | 10         | Removing up vote                 |
|                               |            |                                  |
| Remove Content Vote Up        | 10         | Removing down vote               |
|                               |            |                                  |
| Add Comment                   | 50         | Adding comments to the content   |

Each **Content Message** will always be under an existing **Content Message** which forms a tree root. 

Apart from that, the owner can set **Content Message** to either private or public.

A **Content Message** created in default will be private whereby only the **Content Owner Address** is able to continue creating a new **Child Content Message** under it.

If the **Content Owner Address** sets the **Content Message** to public, anyone can continue to create **Child Content Message** below it.

Anyone can vote up and/or vote down for each **Content Message** which has been created. However, each **Web3 Address** is only allowed to vote up and/or vote down once on a **Content Message**  unless the **Web3 Address** previous vote has been self-removed.

Transactions such as creating **Content Message** , voting and commenting in **Repu** is transparent to the community. Since **Repu** system is a smart contract driven by blockchain technology, the data is available to everyone, anywhere and at any time.

**Repu** comprises three core components written with Solidity smart contracts: -

1. RepuMain (Content)
2. RepuVote
3. RepuComment

## Question

**<u>How do we ensure that the Content Message is correct?</u>**

Community will do the judgement by voting up and/or voting down on every **Content Message** which has been created.

Benefits of involving the public to vote are as follows: -

-  More accurate and correct information is circulated to the public

-  More perspectives can be collected and shared among the public

-  Increased in mutual understanding among the public

-  Adheres with the democratic principles and values


## Case Study

**<u>Scenario 1 - Content Message set to Public</u>**

<div class="align-left"><img width="900" src="/img/repu-scenario-1.png" alt="Repu Scenario"/></div> 

The **Content ID** 1 and **Content ID** 2 has been set as “public”. This would allow any **Web3 Address** to continue to create a **Child Content Message** under **Content ID** 1 and **Content ID** 2.

**<u>Scenario 2 - Content Message set to Private</u>**

<div class="align-left"><img width="900" src="/img/repu-scenario-2.png" alt="Repu Scenario"/></div> 

The **Content ID** 3 has been set as “private”. This would mean that only the **Content Owner Address** of the **Content ID** 3 can continue to create a **Child Content Message** under its own **Content Message**. 

**<u>Scenario 3 - Public create Child Content Message under Private Content Message</u>**

<div class="align-left"><img width="600" src="/img/repu-scenario-6.png" alt="Repu Scenario"/></div>

The **Content ID** X wants to create a **Child Content Message** under the private **Content ID** 8. The system will reject the transaction as **Content Owner Address** has set the **Content ID** 8 to be private.

**<u>Scenario 4 - Voting of Content Message</u>**

<div class="align-left"><img width="1200" src="/img/repu-scenario-3.png" alt="Repu Scenario"/></div> 

Regardless of whether the **Content Message** is set as “public” or “private”, every **Content Message** can be voted by the community. The vote and either be an “up vote” and/or “down vote” depending on whether the community opines that the **Content Message** is a genuine or fake content.

If for example **Content ID** 8's **Content Message** has been “down vote” many times by the community, then the community can see that there is more down votes than up votes.

**<u>Scenario 5 - Removing voting of Content Message</u>**

<div class="align-left"><img width="1200" src="/img/repu-scenario-4.png" alt="Repu Scenario"/></div> 

Additionally, the community may also remove their earlier vote if they think that the **Content Message** appears to be genuine or fake at a later stage. 

**<u>Scenario 6 - Comment on Content Message</u>**

<div class="align-left"><img width="1200" src="/img/repu-scenario-5.png" alt="Repu Scenario"/></div> 

The community will be allowed to comment on each of the **Content Message** to engage in a “discussion” with the respective **Content ID** or even to justify their voting.   

## Notes: 

- Every **Web3 Address** who votes on the **Content Message** can be identified through their **Web3 Address** or the **Content ID**. This creates a  form  of transparency for everyone using the system.

- Every transaction/action will incur a certain amount of cost. Please refer to the table above on cost for specific types of transaction/action. 

## Project AC

### Stay Tuned! Coming Soon!