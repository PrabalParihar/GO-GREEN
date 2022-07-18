.<img width="1440" alt="Screenshot 2022-07-18 at 10 20 39 AM" src="https://user-images.githubusercontent.com/62445763/179447798-94d8ea22-7137-425f-a5f6-92ba7d67c3c4.png">

Our product offers a decentralized approach to collective action. Any user is able to create a bounty for a certain action. Besides setting the title, the description and uploading a representative picture for the claim, they can also specify what proof they expect for submissions and a cut off date. The bounty is created by confirming how much MATIC they want to commit to the prize pool.


<img width="1440" alt="Screenshot 2022-07-18 at 10 22 59 AM" src="https://user-images.githubusercontent.com/62445763/179447834-053b38e8-e6bf-4b95-b906-de7d132b18c8.png">

Once created, others who support the cause can also commit money to the prize pool.
For every MATIC spent, contributors get 1 CoAc token.
The prize pools are staked in Aave to earn interest on MATIC, achieving a profit for our platform and enabling us to not take fees on any transaction.

<img width="1440" alt="Screenshot 2022-07-18 at 10 24 38 AM" src="https://user-images.githubusercontent.com/62445763/179447839-3aea424c-78ce-412e-aeb6-16ab6d3e354f.png">

Individuals can fulfill the created tasks before the cut off date and upload the required proof of their action. On submission, they also have to stake a small amount to prove their seriousness. After the time runs up and the application period ends, the submissions can be reviewed by the community for 7 days

<img width="1440" alt="Screenshot 2022-07-18 at 10 27 24 AM" src="https://user-images.githubusercontent.com/62445763/179447847-b574c27e-9a73-41fa-9d29-c28268620270.png">

If a community member doubts that validity of a claim, they can dispute it. They upload a proof for that stating their reasoning and also stake a small amount to prove their seriousness.


<img width="1440" alt="Screenshot 2022-07-18 at 10 37 38 AM" src="https://user-images.githubusercontent.com/62445763/179448677-9ccb54f5-0f9f-433a-a486-cef2ad3419b0.png">

During the dispute phase, submitted claims that are up for dispute are displayed to users on the platform.  CoAc token holders can either vote in favor of the submitter or the disputer.  A user’s vote power depends on the number of tokens that they hold.
At the end of the 7 days dispute period, if a user’s claim either was not disputed or if at least 50% of the votes on the dispute proposal are in favor of them, the claim is declared valid.
The prize pool of the bounty is split between all valid claims and automatically paid with Gelato.


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

<img width="1440" alt="Screenshot 2022-07-18 at 10 41 05 AM" src="https://user-images.githubusercontent.com/62445763/179448826-e3c4b8d5-9cf8-405a-9027-f9cf995f944a.png">

## How it's made

We used NextJS/React to ensure compatibility and we used polygon as our ecosystem to ensure low gas fees. As our product is aimed at non-crypto native people,
Information about the prize pools, proofs for the claims and disputes are stored on IPFS. The MATIC of the prize pool are staked in Aave lending pools to earn profits for the platform. Without Gelato, users would have to manually withdraw their received money. However, with Gelato, we can ensure automatic payouts.
We are particularly proud of the fact that we have been able to built the whole complex platform over the course of this weekend!

## Contact
# Persons of contact in case there are any questions

Name | #Prabal Pratap Singh|
--- |
Email | amanparihar129@gmail.com |
--- | 
Discord | #prabal#4653 |


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
