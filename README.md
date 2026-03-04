# iGamezGamble

Decentralized sportsbook — place and manage bets on sports events. Built with [Next.js](https://nextjs.org/), [Azuro](https://azuro.org) SDK, and wallet/social login (Privy).

## Video

https://github.com/user-attachments/assets/cfd5ab69-0acd-4d7f-b6a6-93b45c702e88


<img width="1510" height="915" alt="Screenshot_7" src="https://github.com/user-attachments/assets/071d8db3-acc1-41e8-93da-6f929ca0ec5f" />



### Affiliate address
Change the `NEXT_PUBLIC_AFFILIATE_ADDRESS` variable in [.env](/.env) file with your address and other related to project information.

### Social login
Register at https://dashboard.privy.io/account:
- Create a project, go to "Embedded wallets" page, "Smart Wallets" tab, enable it, choose "Safe" (we support only this), configure paymasters for your app chains (https://dashboard.pimlico.io/apikeys).
- Go to "Settings" and copy `App ID`.
- Put value to `NEXT_PUBLIC_PRIVY_APP_ID` variable in [.env](/.env)

